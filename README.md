# Humboldt-Universität zu Berlin (humboldt-universitat-zu-berlin)

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

Humboldt-Universität zu Berlin (HU Berlin) is a public research university in Berlin, Germany, ranked #126 in the QS World University Rankings 2025. This repository catalogs HU Berlin's public developer/API footprint as an [APIs.json](https://apisjson.org) provider profile. The footprint is centered on scholarly and library infrastructure — the edoc Open Access repository (DSpace), the Primus library discovery service (Ex Libris Primo/Alma), and Shibboleth/SAML identity — rather than a unified public API developer portal.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/humboldt-universitat-zu-berlin/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=humboldt-universitat-zu-berlin-api-evangelist&utm_content=repo

## Type

Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Research, Open Access, Library, Germany

## APIs

- **edoc-Server DSpace REST API** — Public REST API of the edoc institutional repository (DSpace 7). Docs: https://edoc-info.hu-berlin.de/en — Base: `https://edoc.hu-berlin.de/server/api`
- **edoc-Server OAI-PMH Interface** — OAI-PMH 2.0 metadata harvesting endpoint. Docs: https://edoc-info.hu-berlin.de/en — Base: `https://edoc.hu-berlin.de/server/oai/request`
- **University Library Primus Discovery (Ex Libris Primo/Alma)** — Central library search portal on Primo/Alma; open APIs exist but are not self-service. Docs: https://www.ub.hu-berlin.de/en/literature-search/catalogues/catalogues
- **HU-IAM Shibboleth Single Sign-On (SAML)** — Shibboleth/SAML SSO operated by CMS; service-provider integration docs. Docs: https://www.cms.hu-berlin.de/de/dl/hu-iam/shibboleth

## Plans

[plans/humboldt-universitat-zu-berlin-plans-pricing.yml](plans/humboldt-universitat-zu-berlin-plans-pricing.yml)

## Rate Limits

[rate-limits/humboldt-universitat-zu-berlin-rate-limits.yml](rate-limits/humboldt-universitat-zu-berlin-rate-limits.yml)

## FinOps

[finops/humboldt-universitat-zu-berlin-finops.yml](finops/humboldt-universitat-zu-berlin-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.hu-berlin.de/en
- GitHub: https://github.com/UB-HU-Berlin
- LinkedIn: https://www.linkedin.com/school/humboldt-universitat-zu-berlin/
- Authentication: https://www.cms.hu-berlin.de/de/dl/hu-iam/shibboleth

## Notes

All listed endpoints were probed live on 2026-06-03 and returned HTTP 200; the OAI-PMH `Identify` request returned valid XML naming the repository "edoc-Server". No endpoints, docs URLs, or properties were fabricated. HU Berlin does not publish a consolidated, self-service public API developer portal. The Primo/Alma and Shibboleth interfaces are documented capabilities of the underlying platforms but are governed access (library/CMS), not open self-service APIs. The AGNES campus management / course catalog system is publicly browsable but no documented public API was confirmed.

## Maintainers

- Kin Lane — kin@apievangelist.com
