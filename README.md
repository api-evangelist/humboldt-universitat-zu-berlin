# Humboldt-Universität zu Berlin

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

Humboldt-Universität zu Berlin (HU Berlin) is a public research university in Berlin, Germany, founded in 1810 and ranked #126 in the QS World University Rankings 2025. Like almost every university, HU is a federation of buyers rather than an API producer: it publishes no developer portal, no API terms, no SDKs and not one OpenAPI of its own, and every OpenAPI in this repository was authored by API Evangelist from live probes and says so in its own info.description. What HU does genuinely operate is scholarly and identity infrastructure on its own hosts. The edoc-Server institutional repository at edoc.hu-berlin.de (DSpace 8, self-hosted by the University Library) exposes an unauthenticated read REST API and a full OAI-PMH 2.0 interface advertising eighteen metadata formats including oai_datacite. The LAUDATIO-Repository for historical linguistic corpora, run by the Corpus Linguistics department with the Computer- und Medienservice, publishes a documented, versioned, public REST API over its Elasticsearch index. HU operates its own Shibboleth/SAML identity provider, registered in DFN-AAI and published to eduGAIN, and is a DataCite member (VLEF) minting 32,950 DOIs under its own prefix 10.18452 across ten registered repositories. Its library discovery is an Ex Libris Primo/Alma tenancy and is not HU engineering. Note for machine consumers: hu-berlin.de web hosts, including the GitLab instance at scm.cms.hu-berlin.de, sit behind an Anubis proof-of-work bot wall that returns HTTP 200 with a JavaScript challenge instead of content — the data hosts (edoc, LAUDATIO) do not.

**Areas:** University · Higher Education · Education · Research · Germany · Berlin · Institutional Repository · Research Data · Open Access · Library · Identity Federation · OAI-PMH

## Humboldt-Universität zu Berlin on APIs.io

Everything profiled for Humboldt-Universität zu Berlin is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/humboldt-universitat-zu-berlin/](https://apis.io/providers/humboldt-universitat-zu-berlin/)** — or go straight to one of the APIs or properties below.

### APIs (11)

- [edoc-Server DSpace REST API](https://apis.io/apis/humboldt-universitat-zu-berlin/edoc-rest/) — Public, unauthenticated read API of the edoc-Server, the Open Access institutional repository of Humboldt-Universität zu Berlin, operated by the University…
- [edoc-Server OAI-PMH 2.0 Interface](https://apis.io/apis/humboldt-universitat-zu-berlin/edoc-oai/) — OAI-PMH 2.0 metadata harvesting endpoint for the edoc institutional repository, on HU's own host. ?verb=Identify returned 200 on 2026-09-01 with…
- [HU-IAM Shibboleth Identity Provider (SAML 2.0)](https://apis.io/apis/humboldt-universitat-zu-berlin/shibboleth-idp/) — Humboldt-Universität zu Berlin operates its own Shibboleth/SAML identity provider, entityID https://shib-idp.cms.hu-berlin.de/idp/shibboleth, registered by…
- [DataCite Membership (VLEF)](https://apis.io/apis/humboldt-universitat-zu-berlin/datacite-membership/) — Humboldt-Universität zu Berlin is a DataCite member — provider symbol VLEF, memberType consortium_organization, country DE, ROR https://ror.org/01hcx6992,…
- [HU Berlin GitLab (scm.cms.hu-berlin.de)](https://apis.io/apis/humboldt-universitat-zu-berlin/hu-gitlab/) — HU's Computer- und Medienservice operates its own GitLab instance at scm.cms.hu-berlin.de, hosting institutional projects including the LAUDATIO repository…
- [University Library Primus Discovery (Ex Libris Primo/Alma tenancy)](https://apis.io/apis/humboldt-universitat-zu-berlin/primo-discovery/) — Primus, the University Library's central search portal, is an Ex Libris Primo deployment backed by Alma, served from hu-berlin.primo.exlibrisgroup.com under…
- [NOMAD Repository (FAIRmat) — HU DOI tenancy](https://apis.io/apis/humboldt-universitat-zu-berlin/nomad-repository/) — The NOMAD Repository for computational materials-science data is registered under HU Berlin's DataCite membership as repository tib.hu ("HU Berlin - NOMAD…
- [GenderOpen Repositorium — HU DOI tenancy](https://apis.io/apis/humboldt-universitat-zu-berlin/genderopen/) — GenderOpen is the shared open-access repository for gender studies run jointly by the Freie Universität Berlin, Humboldt-Universität zu Berlin and…
- [Humboldt-Universität zu Berlin Annotations API](https://apis.io/apis/humboldt-universitat-zu-berlin/humboldt-universitat-zu-berlin-annotations-api/) — Annotation layers and their preparation metadata
- [Humboldt-Universität zu Berlin Corpora API](https://apis.io/apis/humboldt-universitat-zu-berlin/humboldt-universitat-zu-berlin-corpora-api/) — Published historical corpora and their header metadata
- [Humboldt-Universität zu Berlin Documents API](https://apis.io/apis/humboldt-universitat-zu-berlin/humboldt-universitat-zu-berlin-documents-api/) — Documents belonging to a published corpus

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Humboldt Universitat Zu Berlin Agentic Access](https://apis.io/agentic-access/humboldt-universitat-zu-berlin/humboldt-universitat-zu-berlin-agentic-access/)

#### JSON Schema (3)

The data models the API reads and writes.

- [DSpace Collection](https://apis.io/schemas/humboldt-universitat-zu-berlin/humboldt-universitat-zu-berlin-collection/)
- [DSpace Community](https://apis.io/schemas/humboldt-universitat-zu-berlin/humboldt-universitat-zu-berlin-community/)
- [DSpace Item](https://apis.io/schemas/humboldt-universitat-zu-berlin/humboldt-universitat-zu-berlin-item/)

#### JSON Structure (2)

Data models expressed in JSON Structure.

- [Humboldt Universitat Zu Berlin Community Structure](https://apis.io/json-structure/humboldt-universitat-zu-berlin/humboldt-universitat-zu-berlin-community-structure/)
- [Humboldt Universitat Zu Berlin Item Structure](https://apis.io/json-structure/humboldt-universitat-zu-berlin/humboldt-universitat-zu-berlin-item-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Humboldt Universitat Zu Berlin Context](https://apis.io/jsonld/humboldt-universitat-zu-berlin/humboldt-universitat-zu-berlin-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [edoc-Server DSpace REST API Vocabulary](https://apis.io/vocabularies/humboldt-universitat-zu-berlin/humboldt-universitat-zu-berlin-vocabulary/)

#### Examples (3)

Example requests and responses.

- [Humboldt Universitat Zu Berlin Get Collection Example](https://apis.io/examples/humboldt-universitat-zu-berlin/humboldt-universitat-zu-berlin-get-collection-example/)
- [Humboldt Universitat Zu Berlin List Communities Example](https://apis.io/examples/humboldt-universitat-zu-berlin/humboldt-universitat-zu-berlin-list-communities-example/)
- [Humboldt Universitat Zu Berlin Search Objects Example](https://apis.io/examples/humboldt-universitat-zu-berlin/humboldt-universitat-zu-berlin-search-objects-example/)

#### Collections (3)

Postman and Open Collection request collections.

- [edoc-Server DSpace REST API (Humboldt-Universität zu Berlin) Core API](https://apis.io/collections/humboldt-universitat-zu-berlin/open-humboldt-universitat-zu-berlin-core-api/)
- [edoc-Server DSpace REST API (Humboldt-Universität zu Berlin) Core Discovery API](https://apis.io/collections/humboldt-universitat-zu-berlin/open-humboldt-universitat-zu-berlin-discovery-api/)
- [edoc-Server DSpace REST API (Humboldt-Universität zu Berlin) Core Root API](https://apis.io/collections/humboldt-universitat-zu-berlin/open-humboldt-universitat-zu-berlin-root-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Humboldt-Universität zu Berlin — jsonschema rules](https://apis.io/rules/humboldt-universitat-zu-berlin/humboldt-universitat-zu-berlin-jsonschema-spectral-rules/)
- [Humboldt-Universität zu Berlin API Rules](https://apis.io/rules/humboldt-universitat-zu-berlin/humboldt-universitat-zu-berlin-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Humboldt Universitat Zu Berlin Domain Security](https://apis.io/security/humboldt-universitat-zu-berlin/humboldt-universitat-zu-berlin-domain-security/)
- [Humboldt Universitat Zu Berlin Vulnerability Disclosure](https://apis.io/security/humboldt-universitat-zu-berlin/humboldt-universitat-zu-berlin-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Humboldt Universitat Zu Berlin Plans Pricing](https://apis.io/plans/humboldt-universitat-zu-berlin/humboldt-universitat-zu-berlin-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Humboldt Universitat Zu Berlin Rate Limits](https://apis.io/rate-limits/humboldt-universitat-zu-berlin/humboldt-universitat-zu-berlin-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Humboldt Universitat Zu Berlin Finops](https://apis.io/finops/humboldt-universitat-zu-berlin/humboldt-universitat-zu-berlin-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.hu-berlin.de/en)
- [API reference](https://www.laudatio-repository.org/docs/elasticapi)
- [Terms of service](https://www.hu-berlin.de/de/hu/impressum)
- [Privacy policy](https://www.hu-berlin.de/de/hu/impressum/datenschutzerklaerung)
- [GitHub](https://github.com/UB-HU-Berlin)

## API Evangelist rating

**Kin Score 22.7** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 62.5 |
| Contract quality | 31.3 |
| Contract governance | 28.0 |
| Operational transparency | 7.9 |
| Developer ergonomics | 7.1 |
| Access clarity | 5.3 |

**Agent readiness 23.6** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | — |
| OpenAPI Examples | partial |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 30.4** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/humboldt-universitat-zu-berlin/](https://apis.io/providers/humboldt-universitat-zu-berlin/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Humboldt-Universität zu Berlin: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/humboldt-universitat-zu-berlin/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
