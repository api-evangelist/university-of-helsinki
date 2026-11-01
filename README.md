# University of Helsinki

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

The University of Helsinki is Finland's oldest and largest multidisciplinary research university, founded in 1640, and it is one of the very few institutions in this cohort that operates a real, first-party API program rather than only renting vendor platforms. It runs its own Gravitee API gateway at gw.api.helsinki.fi behind a public developer portal at api.helsinki.fi, listing fifteen public APIs — organisations, buildings and spaces, employee and group directories, service management, the application-portfolio register, network registry, and the CMS behind helsinki.fi and the course pages — twelve of which publish a readable OpenAPI. Alongside that sit genuinely institution-operated scholarly and identity infrastructure: Helda (DSpace 7.6.2) and the newer HY Data Catalogue (DSpace 9.0), three live OAI-PMH endpoints, the Editori open-publishing service, the Shibboleth/OIDC identity provider at login.helsinki.fi with sixteen entities registered in the Haka federation, and the Finnish Biodiversity Information Facility (api.laji.fi, 177 paths), which is run by Luomus, a University institute. What the University does NOT author is equally important and is recorded here as tenancy rather than as its own work: Sisu/Kori is Funidata's, the research portal is Elsevier Pure, and Helka is Ex Libris Primo. The gateway is affiliation-gated — keyless access is disabled and portal self-registration is off — so the catalogue and every specification are readable by anyone, while a credential requires a university or Haka identity.

**Areas:** Education · Higher Education · University · Finland · Nordic · Research · Open Data · Research Data · Institutional Repository · OAI-PMH · Identity Federation · API Gateway

## University of Helsinki on APIs.io

Everything profiled for University of Helsinki is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/university-of-helsinki/](https://apis.io/providers/university-of-helsinki/)** — or go straight to one of the APIs or properties below.

### APIs (97)

- [University of Helsinki API Portal (Gravitee)](https://apis.io/apis/university-of-helsinki/api-gateway/) — The University's own API developer portal and gateway — a self-hosted Gravitee API Management deployment. The portal REST API answers anonymously and is, in…
- [Dependency Track](https://apis.io/apis/university-of-helsinki/dependency-track/) — SBOM upload to the University's Dependency Track instance from external networks. Public and running in the portal, but publishes no OpenAPI page, so no…
- [Flamma Liferay Headless API](https://apis.io/apis/university-of-helsinki/flamma-liferay-headless/) — Liferay headless delivery API for Flamma, the staff intranet, distributed through the University gateway. No OpenAPI page is published; the upstream…
- [Internal Guide CMS JSON-API](https://apis.io/apis/university-of-helsinki/internal-guide-cms/) — Authenticated access to the Drupal JSON:API behind the internal guide, covering published and unpublished content. No OpenAPI page is published.
- [Helda DSpace REST API](https://apis.io/apis/university-of-helsinki/helda-rest/) — Public HAL REST API for Helda, the University's open institutional repository, running DSpace 7.6.2. Discovery/search, items, collections, communities and…
- [Helda OAI-PMH Metadata Interface](https://apis.io/apis/university-of-helsinki/helda-oai/) — OAI-PMH 2.0 harvesting endpoint for Helda. Identify returns repositoryName "Helda" with an earliest datestamp of 1976-05-13, and ListMetadataFormats returns…
- [HY Data Catalogue DSpace REST API](https://apis.io/apis/university-of-helsinki/datakatalogi-rest/) — A SECOND, separate DSpace deployment — datakatalogi.helsinki.fi, running DSpace 9.0 with dspaceName "HyDatacatalogue" — cataloguing research DATA rather…
- [HY Data Catalogue OAI-PMH Interface](https://apis.io/apis/university-of-helsinki/datakatalogi-oai/) — OAI-PMH 2.0 endpoint for the HY Data Catalogue. Identify returns repositoryName "HyDatacatalogue", adminEmail datakatalogi@helsinki.fi, granularity…
- [Editori (journals.helsinki.fi) OAI-PMH Interface](https://apis.io/apis/university-of-helsinki/editori-oai/) — OAI-PMH 2.0 endpoint for Editori, the University's open publishing service (PKP Open Journal Systems). Identify returns repositoryName "Editori - Avoimen…
- [HY Login Service — Shibboleth IdP + OpenID Connect](https://apis.io/apis/university-of-helsinki/identity-provider/) — The University's identity provider at login.helsinki.fi, machine-readable twice over. SAML: GET /idp/shibboleth returns an EntityDescriptor with entityID…
- [Sisu (Kori) Student Information System — University of Helsinki tenant](https://apis.io/apis/university-of-helsinki/sisu-kori/) — TENANT RELATIONSHIP, NOT A UNIVERSITY CONTRACT. The University runs its own instance of Sisu, the student information system built by Funidata Oy and shared…
- [University of Helsinki Research Portal — Elsevier Pure tenant](https://apis.io/apis/university-of-helsinki/research-portal/) — TENANT RELATIONSHIP. researchportal.helsinki.fi is an Elsevier Pure deployment (the page markup identifies Pure and Elsevier directly). It is the…
- [Helka Library Discovery — Ex Libris Primo tenant](https://apis.io/apis/university-of-helsinki/helka/) — TENANT RELATIONSHIP. helka.helsinki.fi redirects to an Ex Libris Primo discovery interface with view identifier 358UOH_INST:VU1. Library discovery is the…
- [University of Helsinki All Node Attributes API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-allnodeattributes-api/) — The AllNodeAttributes API from University of Helsinki — 1 operation(s) for allnodeattributes.
- [University of Helsinki All Successors And Predecessors API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-allsuccessorsandpredecessors-api/) — The AllSuccessorsAndPredecessors API from University of Helsinki — 1 operation(s) for allsuccessorsandpredecessors.
- [University of Helsinki Annotations API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-annotations-api/) — The Annotations API from University of Helsinki — 3 operation(s) for annotations.
- [University of Helsinki /api API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-api-api/) — dawasync API rest service
- [University of Helsinki API user API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-api-user-api/) — The API user API from University of Helsinki — 3 operation(s) for api user.
- [University of Helsinki Areas API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-areas-api/) — The Areas API from University of Helsinki — 2 operation(s) for areas.
- [University of Helsinki Audio API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-audio-api/) — The Audio API from University of Helsinki — 7 operation(s) for audio.
- [University of Helsinki Authentication event API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-authentication-event-api/) — The Authentication event API from University of Helsinki — 1 operation(s) for authentication event.
- [University of Helsinki Autocomplete API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-autocomplete-api/) — The Autocomplete API from University of Helsinki — 3 operation(s) for autocomplete.
- [University of Helsinki Checklist API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-checklist-api/) — The Checklist API from University of Helsinki — 2 operation(s) for checklist.
- [University of Helsinki Checklist Versions API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-checklist-versions-api/) — The Checklist Versions API from University of Helsinki — 2 operation(s) for checklist versions.
- [University of Helsinki Collections API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-collections-api/) — The Collections API from University of Helsinki — 5 operation(s) for collections.
- [University of Helsinki Company Contact API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-companycontact-api/) — The CompanyContact API from University of Helsinki — 2 operation(s) for companycontact.
- [University of Helsinki Company Organization API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-companyorganization-api/) — The CompanyOrganization API from University of Helsinki — 3 operation(s) for companyorganization.
- [University of Helsinki Company Title API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-companytitle-api/) — The CompanyTitle API from University of Helsinki — 1 operation(s) for companytitle.
- [University of Helsinki Contact API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-contact-api/) — The Contact API from University of Helsinki — 2 operation(s) for contact.
- [University of Helsinki Content - Course API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-content-course-api/) — Content type Course of type Content. Contains information related to a course, such as introduction text and an image.
- [University of Helsinki Coordinates API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-coordinates-api/) — The Coordinates API from University of Helsinki — 1 operation(s) for coordinates.
- [University of Helsinki Documents API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-documents-api/) — The Documents API from University of Helsinki — 7 operation(s) for documents.
- [University of Helsinki /dynamicorder API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-dynamicorder-api/) — The /dynamicorder API from University of Helsinki — 8 operation(s) for /dynamicorder.
- [University of Helsinki Education Units API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-educationunits-api/) — The EducationUnits API from University of Helsinki — 2 operation(s) for educationunits.
- [University of Helsinki Feedback API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-feedback-api/) — The Feedback API from University of Helsinki — 1 operation(s) for feedback.
- [University of Helsinki Field Of Science API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-fieldofscience-api/) — The FieldOfScience API from University of Helsinki — 1 operation(s) for fieldofscience.
- [University of Helsinki Filter API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-filter-api/) — The Filter API from University of Helsinki — 2 operation(s) for filter.
- [University of Helsinki Finance And Old Research API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-financeandoldresearch-api/) — The FinanceAndOldResearch API from University of Helsinki — 1 operation(s) for financeandoldresearch.
- [University of Helsinki Finance Units API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-financeunits-api/) — The FinanceUnits API from University of Helsinki — 2 operation(s) for financeunits.
- [University of Helsinki Finance Units Public API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-financeunitspublic-api/) — The FinanceUnitsPublic API from University of Helsinki — 1 operation(s) for financeunitspublic.
- [University of Helsinki Finance Units Unique Code API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-financeunitsuniquecode-api/) — The FinanceUnitsUniqueCode API from University of Helsinki — 1 operation(s) for financeunitsuniquecode.
- [University of Helsinki Form Permissions API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-form-permissions-api/) — The Form Permissions API from University of Helsinki — 3 operation(s) for form permissions.
- [University of Helsinki Forms API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-forms-api/) — The Forms API from University of Helsinki — 4 operation(s) for forms.
- [University of Helsinki Geo Convert API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-geoconvert-api/) — The GeoConvert API from University of Helsinki — 6 operation(s) for geoconvert.
- [University of Helsinki Google Maps API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-google-maps-api/) — The Google Maps API from University of Helsinki — 1 operation(s) for google maps.
- [University of Helsinki Hosts API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-hosts-api/) — The Hosts API from University of Helsinki — 3 operation(s) for hosts.
- [University of Helsinki Hr Organization API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-hrorganization-api/) — The HrOrganization API from University of Helsinki — 3 operation(s) for hrorganization.
- [University of Helsinki HTML To PDF API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-html-to-pdf-api/) — The HTML To PDF API from University of Helsinki — 1 operation(s) for html to pdf.
- [University of Helsinki Human Resources And Research Groups API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-humanresourcesandresearchgroups-api/) — The HumanResourcesAndResearchGroups API from University of Helsinki — 1 operation(s) for humanresourcesandresearchgroups.
- [University of Helsinki Human Resources Iam Group Prefix API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-humanresourcesiamgroupprefix-api/) — The HumanResourcesIamGroupPrefix API from University of Helsinki — 1 operation(s) for humanresourcesiamgroupprefix.
- [University of Helsinki Human Resources Subunit To Unit API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-humanresourcessubunittounit-api/) — The HumanResourcesSubunitToUnit API from University of Helsinki — 1 operation(s) for humanresourcessubunittounit.
- [University of Helsinki Human Resources With Level API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-humanresourceswithlevel-api/) — The HumanResourcesWithLevel API from University of Helsinki — 1 operation(s) for humanresourceswithlevel.
- [University of Helsinki Images API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-images-api/) — The Images API from University of Helsinki — 6 operation(s) for images.
- [University of Helsinki Informal Taxon Groups API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-informal-taxon-groups-api/) — The Informal Taxon Groups API from University of Helsinki — 7 operation(s) for informal taxon groups.
- [University of Helsinki Information API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-information-api/) — The Information API from University of Helsinki — 1 operation(s) for information.
- [University of Helsinki JSON-LD context API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-json-ld-context-api/) — The JSON-LD context API from University of Helsinki — 1 operation(s) for json-ld context.
- [University of Helsinki Logger API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-logger-api/) — The Logger API from University of Helsinki — 2 operation(s) for logger.
- [University of Helsinki Login API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-login-api/) — The Login API from University of Helsinki — 2 operation(s) for login.
- [University of Helsinki /machine API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-machine-api/) — The /machine API from University of Helsinki — 1 operation(s) for /machine.
- [University of Helsinki Metadata API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-metadata-api/) — The Metadata API from University of Helsinki — 9 operation(s) for metadata.
- [University of Helsinki Named places API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-named-places-api/) — The Named places API from University of Helsinki — 3 operation(s) for named places.
- [University of Helsinki News API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-news-api/) — The News API from University of Helsinki — 4 operation(s) for news.
- [University of Helsinki Nodes In Multiple Hierarchies API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-nodesinmultiplehierarchies-api/) — The NodesInMultipleHierarchies API from University of Helsinki — 1 operation(s) for nodesinmultiplehierarchies.
- [University of Helsinki Notifications API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-notifications-api/) — The Notifications API from University of Helsinki — 2 operation(s) for notifications.
- [University of Helsinki Official Units API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-officialunits-api/) — The OfficialUnits API from University of Helsinki — 2 operation(s) for officialunits.
- [University of Helsinki /order API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-order-api/) — The /order API from University of Helsinki — 1 operation(s) for /order.
- [University of Helsinki Organization API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-organization-api/) — The Organization API from University of Helsinki — 2 operation(s) for organization.
- [University of Helsinki Organizations API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-organizations-api/) — The Organizations API from University of Helsinki — 2 operation(s) for organizations.
- [University of Helsinki Person API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-person-api/) — The Person API from University of Helsinki — 6 operation(s) for person.
- [University of Helsinki Publications API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-publications-api/) — The Publications API from University of Helsinki — 1 operation(s) for publications.
- [University of Helsinki Red List Evaluation Groups API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-red-list-evaluation-groups-api/) — The Red List Evaluation Groups API from University of Helsinki — 7 operation(s) for red list evaluation groups.
- [University of Helsinki Research Groups API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-researchgroups-api/) — The ResearchGroups API from University of Helsinki — 1 operation(s) for researchgroups.
- [University of Helsinki Research Organization API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-researchorganization-api/) — The ResearchOrganization API from University of Helsinki — 1 operation(s) for researchorganization.
- [University of Helsinki Research Resources API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-researchresources-api/) — The ResearchResources API from University of Helsinki — 1 operation(s) for researchresources.
- [University of Helsinki Shorthands API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-shorthands-api/) — The Shorthands API from University of Helsinki — 4 operation(s) for shorthands.
- [University of Helsinki Sound identification API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-sound-identification-api/) — The Sound identification API from University of Helsinki — 1 operation(s) for sound identification.
- [University of Helsinki Sources API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-sources-api/) — The Sources API from University of Helsinki — 2 operation(s) for sources.
- [University of Helsinki /ss API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-ss-api/) — The /ss API from University of Helsinki — 3 operation(s) for /ss.
- [University of Helsinki Steering Group API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-steeringgroup-api/) — The SteeringGroup API from University of Helsinki — 3 operation(s) for steeringgroup.
- [University of Helsinki Steering Groups API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-steeringgroups-api/) — The SteeringGroups API from University of Helsinki — 1 operation(s) for steeringgroups.
- [University of Helsinki Study Search API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-study-search-api/) — Study search content. The API returns the study options and/or degree programmes content for University of Helsinki in an indexable format. The API strives…
- [University of Helsinki Suggestion API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-suggestion-api/) — The Suggestion API from University of Helsinki — 1 operation(s) for suggestion.
- [University of Helsinki Taxa API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-taxa-api/) — The Taxa API from University of Helsinki — 12 operation(s) for taxa.
- [University of Helsinki /ticket API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-ticket-api/) — The /ticket API from University of Helsinki — 1 operation(s) for /ticket.
- [University of Helsinki Title API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-title-api/) — The Title API from University of Helsinki — 1 operation(s) for title.
- [University of Helsinki Trait API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-trait-api/) — The Trait API from University of Helsinki — 32 operation(s) for trait.
- [University of Helsinki University Of Helsinki Group API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-universityofhelsinkigroup-api/) — The UniversityOfHelsinkiGroup API from University of Helsinki — 1 operation(s) for universityofhelsinkigroup.
- [University of Helsinki University Of Helsinki Subunit To Unit API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-universityofhelsinkisubunittounit-api/) — The UniversityOfHelsinkiSubunitToUnit API from University of Helsinki — 1 operation(s) for universityofhelsinkisubunittounit.
- [University of Helsinki /v1 API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-v1-api/) — Employee Information REST service
- [University of Helsinki V1/building/ API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-v1-building-api/) — University buildings rest service
- [University of Helsinki V1/space/ API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-v1-space-api/) — University spaces rest service
- [University of Helsinki Warehouse API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-warehouse-api/) — The Warehouse API from University of Helsinki — 23 operation(s) for warehouse.
- [University of Helsinki Group API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-group-api/) — The Group API from University of Helsinki — 1 operation(s) for group.
- [University of Helsinki Groupnames API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-groupnames-api/) — The Groupnames API from University of Helsinki — 1 operation(s) for groupnames.
- [University of Helsinki Groups API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-groups-api/) — The Groups API from University of Helsinki — 1 operation(s) for groups.
- [University of Helsinki Steeringgroupspeople API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-steeringgroupspeople-api/) — The Steeringgroupspeople API from University of Helsinki — 1 operation(s) for steeringgroupspeople.
- [University of Helsinki Human Resources API](https://apis.io/apis/university-of-helsinki/university-of-helsinki-human-resources-api/) — The Human Resources API from University of Helsinki — 1 operation(s) for human resources.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### GraphQL (1)

GraphQL schemas.

- [GraphQL at the University of Helsinki](https://apis.io/graphqls/university-of-helsinki/university-of-helsinki-graphql/)

#### JSON Schema (11)

The data models the API reads and writes.

- [University of Helsinki - Contact Search API — component schemas](https://apis.io/schemas/university-of-helsinki/university-of-helsinki-contact-search-api-schemas/)
- [University of Helsinki - Courses content machine - JSON API — component schemas](https://apis.io/schemas/university-of-helsinki/university-of-helsinki-course-pages-cms-schemas/)
- [EmployeeInformationAPI — component schemas](https://apis.io/schemas/university-of-helsinki/university-of-helsinki-employeeinformationapi-schemas/)
- [Laji API — component schemas](https://apis.io/schemas/university-of-helsinki/university-of-helsinki-finbif-laji-schemas/)
- [General Efecte API — component schemas](https://apis.io/schemas/university-of-helsinki/university-of-helsinki-general-efecte-api-schemas/)
- [Helsinki.fi content — component schemas](https://apis.io/schemas/university-of-helsinki/university-of-helsinki-helsinki-fi-content-schemas/)
- [HY Building API — component schemas](https://apis.io/schemas/university-of-helsinki/university-of-helsinki-hy-building-api-schemas/)
- [Organisation Registry Public API — component schemas](https://apis.io/schemas/university-of-helsinki/university-of-helsinki-hy-organisation-api-schemas/)
- [network registry — component schemas](https://apis.io/schemas/university-of-helsinki/university-of-helsinki-network-registry-api-schemas/)
- [HY Person/Group API — component schemas](https://apis.io/schemas/university-of-helsinki/university-of-helsinki-persongroup-schemas/)
- [ServiceAPI — component schemas](https://apis.io/schemas/university-of-helsinki/university-of-helsinki-serviceapi-schemas/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [University Of Helsinki Context](https://apis.io/jsonld/university-of-helsinki/university-of-helsinki-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [University of Helsinki — openapi rules](https://apis.io/rules/university-of-helsinki/university-of-helsinki-openapi-spectral-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [University Of Helsinki Authentication](https://apis.io/security/university-of-helsinki/university-of-helsinki-authentication/)
- [University Of Helsinki Domain Security](https://apis.io/security/university-of-helsinki/university-of-helsinki-domain-security/)
- [University Of Helsinki Vulnerability Disclosure](https://apis.io/security/university-of-helsinki/university-of-helsinki-vulnerability-disclosure/)

#### OAuth scopes (1)

The permissions the API asks for.

- [University Of Helsinki Scopes](https://apis.io/scopes/university-of-helsinki/university-of-helsinki-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [University Of Helsinki Plans Pricing](https://apis.io/plans/university-of-helsinki/university-of-helsinki-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [University Of Helsinki Rate Limits](https://apis.io/rate-limits/university-of-helsinki/university-of-helsinki-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [University Of Helsinki Finops](https://apis.io/finops/university-of-helsinki/university-of-helsinki-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.helsinki.fi/en)
- [Documentation](https://api.helsinki.fi/portal/)
- [API reference](https://api.helsinki.fi/portal/environments/DEFAULT/apis)
- [Blog](https://blogs.helsinki.fi/)
- [Privacy policy](https://www.helsinki.fi/en/about-us/processing-data-university/data-protection)
- [GitHub](https://github.com/UniversityofHelsinki)

## API Evangelist rating

**Kin Score 49.2** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 74.1 |
| Contract quality | 63.3 |
| Contract governance | 29.5 |
| Operational transparency | 21.1 |
| Developer ergonomics | 40.5 |
| Access clarity | 42.1 |

**Agent readiness 25.7** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | mostly (partial credit) |

**Regulatory alignment 44.1** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/university-of-helsinki/](https://apis.io/providers/university-of-helsinki/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for University of Helsinki: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/university-of-helsinki/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
