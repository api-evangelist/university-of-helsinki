# University of Helsinki (university-of-helsinki)

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
