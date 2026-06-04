# Humboldt-Universität zu Berlin (humboldt-universitat-zu-berlin)

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
