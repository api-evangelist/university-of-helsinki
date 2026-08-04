# University of Helsinki (university-of-helsinki)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Founded in 1640, the University of Helsinki is Finland's oldest and largest multidisciplinary research university, ranked #68 in the QS World University Rankings 2025. This repository catalogs its public developer and API footprint as an [APIs.json](https://apisjson.org) provider profile for the API Evangelist network.

- APIs.json: <https://raw.githubusercontent.com/api-evangelist/university-of-helsinki/refs/heads/main/apis.yml>
- Run with Naftiko: <https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-helsinki-api-evangelist&utm_content=repo>

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Finland, Research, Open Data, Institutional Repository, OAI-PMH

## APIs

- **Helda DSpace REST API** — Public REST API (DSpace 7.6.2) for the university's open institutional repository of research publications, dissertations, and theses. Docs: <https://helda.helsinki.fi/server/api>
- **Helda OAI-PMH Metadata Interface** — OAI-PMH metadata-harvesting endpoint for Helda's open-access content. Docs: <https://helda.helsinki.fi/server/oai/request?verb=Identify>
- **Sisu (Kori) Student Information System API** — Funidata Sisu GraphQL/REST APIs for academic administration; institution/partner-gated, no public self-service docs. Docs: <https://www.funidata.fi/en/services/sisu>

## Plans

- [plans/university-of-helsinki-plans-pricing.yml](plans/university-of-helsinki-plans-pricing.yml)

## Rate Limits

- [rate-limits/university-of-helsinki-rate-limits.yml](rate-limits/university-of-helsinki-rate-limits.yml)

## FinOps

- [finops/university-of-helsinki-finops.yml](finops/university-of-helsinki-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: <https://www.helsinki.fi/en>
- GitHub: <https://github.com/UniversityofHelsinki>
- LinkedIn: <https://www.linkedin.com/school/university-of-helsinki/>
- Review: [review.yml](review.yml)

## Notes

All cataloged endpoints were probed live on 2026-06-03. The Helda REST API and OAI-PMH interface both returned HTTP 200 with valid DSpace 7.6.2 responses. The official GitHub org (UniversityofHelsinki, 42 public repos) and Student Services org (UH-StudentServices) both resolve. The Sisu/Kori student information system is real but auth-gated with no public developer documentation for the UH tenant. The previously documented Helsinki University Library API (api.hulib.helsinki.fi) did not resolve and was deliberately not cataloged as a live API. No endpoints were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
