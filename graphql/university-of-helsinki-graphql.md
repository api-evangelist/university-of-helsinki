<!-- x-method: searched -->
<!-- generated: 2026-08-30 -->
<!-- source: live probes against sisu.helsinki.fi and gw.api.helsinki.fi, 2026-08-30 -->

# GraphQL at the University of Helsinki

**The University of Helsinki publishes no GraphQL API of its own.** This file records that
absence, and corrects an earlier version of it that credited the University with a GraphQL
surface that is not the University's.

## What the earlier profile said, and why it was wrong

The 2026-06-03 profile listed "Sisu (Kori) Student Information System API" as a University of
Helsinki GraphQL API. Sisu is a product of **Funidata Oy**, sold to and shared across Finnish
universities. The University runs its own instance at `sisu.helsinki.fi`, so the data behind it is
the University's — but the schema, the resolvers and the contract are Funidata's, identical at
every Sisu customer. Under the university pipeline's operator axis that is
`x-operator: tenant`, and a tenant's vendor contract is never saved under the institution's slug.

The tell is in the tenant instance's own error responses:

```
GET https://sisu.helsinki.fi/kori/api/module-search?limit=1   ->  400 application/json
{"cause":null,"stackTrace":[],"deeper":[],
 "message":"AT_LEAST_ONE_SEARCH_PARAM_REQUIRED",
 "suppressed":[],"localizedMessage":"AT_LEAST_ONE_SEARCH_PARAM_REQUIRED"}
```

and, on a malformed path, `fi.helsinki.otm.common.model.OtmId` with the identifier pattern
`/([a-zA-Z]{2,5})-[A-Za-z0-9_\-]{1,58}/`. OTM — *oppijan tietomalli* — is Funidata's learner data
model. The hostname is the University's; the model is not.

## What was probed

| Surface | Result |
|---|---|
| `https://sisu.helsinki.fi/kori/api/` | 500 JSON — the Kori **REST** surface is live and answers without a credential |
| `https://sisu.helsinki.fi/kori/api/module-search` | 400 JSON, Funidata OTM error envelope |
| University Gravitee gateway, all 15 public APIs | REST only — no GraphQL entrypoint is published in the portal |
| 13 harvested OpenAPI documents | no GraphQL endpoint declared in any of them |

No `/graphql` endpoint was found on `gw.api.helsinki.fi`, `api.helsinki.fi`, `helda.helsinki.fi`,
`datakatalogi.helsinki.fi` or `api.laji.fi`.

## Where the University's real programmable surfaces are instead

REST and protocol endpoints, not GraphQL:

- **Gravitee gateway** — 15 public APIs at `https://gw.api.helsinki.fi`, 12 with published OpenAPI.
- **FinBIF Laji API** — `https://api.laji.fi`, 177 paths, operated by Luomus (a University institute).
- **DSpace HAL REST** — Helda (7.6.2) and the HY Data Catalogue (9.0).
- **OAI-PMH** — three live endpoints (Helda, HY Data Catalogue, Editori).
- **Identity** — Shibboleth SAML metadata and an OpenID Connect discovery document at
  `login.helsinki.fi`.

See `apis.yml` for the full inventory with `x-operator` on every entry.
