# Haystack / deepset (haystack-ai)

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

Haystack is deepset's open-source Python framework for building context-engineered, production-ready LLM applications - modular Pipelines and agent workflows assembled from 100+ Components and document stores for RAG, semantic search, and agents. Haystack pipelines deploy as REST services via Hayhooks, and the commercial deepset AI Platform (deepset Cloud) exposes a hosted REST API at api.cloud.deepset.ai for pipelines, search, files, and workspaces.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/haystack-ai/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/haystack-ai/refs/heads/main/apis.yml)

## Tags

- AI
- LLM
- RAG
- Open Source
- Orchestration

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Haystack Framework (Open Source)

Apache-2.0 licensed Python framework for composable LLM orchestration. Build modular Pipelines from Components (retrievers, routers, embedders, generators, evaluators) over Document Stores for RAG, semantic search, and agents. Programmatic library/SDK surface, not a hosted REST API.

- **Human URL:** [https://docs.haystack.deepset.ai/docs/intro](https://docs.haystack.deepset.ai/docs/intro)
- **Base URL:** `https://github.com/deepset-ai/haystack`

#### Tags

- Framework
- Python
- Pipelines
- Open Source

#### Properties

- [Documentation](https://docs.haystack.deepset.ai/docs/intro)
- [API Reference](https://docs.haystack.deepset.ai/reference)
- [GitHub](https://github.com/deepset-ai/haystack)

### Hayhooks REST Deployment

Hayhooks turns a Haystack pipeline into a self-hosted REST API (and optional MCP server) with one command, auto-generating OpenAPI/Swagger docs and HTTP run endpoints. The deployed surface is generated per pipeline and self-hosted, not a fixed public API.

- **Human URL:** [https://github.com/deepset-ai/hayhooks](https://github.com/deepset-ai/hayhooks)
- **Base URL:** `https://github.com/deepset-ai/hayhooks`

#### Tags

- REST
- Deployment
- Pipelines
- MCP

#### Properties

- [Documentation](https://docs.haystack.deepset.ai/docs/hayhooks)
- [GitHub](https://github.com/deepset-ai/hayhooks)

### deepset Cloud API - Pipelines

Hosted REST API to create, list, deploy, and undeploy Haystack pipelines inside a deepset Cloud workspace. Bearer-authenticated under /api/v1/workspaces/{workspace}/pipelines.

- **Human URL:** [https://docs.cloud.deepset.ai/reference/api-overview](https://docs.cloud.deepset.ai/reference/api-overview)
- **Base URL:** `https://api.cloud.deepset.ai/api/v1`

#### Tags

- Pipelines
- Deployment
- deepset Cloud

#### Properties

- [Documentation](https://docs.cloud.deepset.ai/docs/create-a-pipeline-with-rest-api)
- [API Reference](https://docs.cloud.deepset.ai/reference/api-overview)
- [OpenAPI](openapi/haystack-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/haystack-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/haystack-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### deepset Cloud API - Search

Runs queries against a deployed pipeline, returning answers and retrieved documents. POST /api/v1/workspaces/{workspace}/pipelines/{pipeline}/search with queries, filters, and runtime params.

- **Human URL:** [https://docs.cloud.deepset.ai/docs/run-a-search](https://docs.cloud.deepset.ai/docs/run-a-search)
- **Base URL:** `https://api.cloud.deepset.ai/api/v1`

#### Tags

- Search
- Query
- RAG
- deepset Cloud

#### Properties

- [Documentation](https://docs.cloud.deepset.ai/docs/run-a-search)
- [OpenAPI](openapi/haystack-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/haystack-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/haystack-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### deepset Cloud API - Files

Uploads, lists, and deletes files in a workspace, updates file metadata, and manages chunked upload sessions for indexing into pipelines and indexes.

- **Human URL:** [https://docs.cloud.deepset.ai/docs/upload-files](https://docs.cloud.deepset.ai/docs/upload-files)
- **Base URL:** `https://api.cloud.deepset.ai/api/v1`

#### Tags

- Files
- Upload
- Indexing
- deepset Cloud

#### Properties

- [Documentation](https://docs.cloud.deepset.ai/docs/upload-files)
- [OpenAPI](openapi/haystack-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/haystack-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/haystack-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### deepset Cloud API - Workspaces

Creates, lists, and deletes workspaces - the isolation boundary that holds a deepset Cloud account's pipelines and data. Pipelines and data are not shared across workspaces.

- **Human URL:** [https://docs.cloud.deepset.ai/reference/api-overview](https://docs.cloud.deepset.ai/reference/api-overview)
- **Base URL:** `https://api.cloud.deepset.ai/api/v1`

#### Tags

- Workspaces
- Organization
- deepset Cloud

#### Properties

- [API Reference](https://docs.cloud.deepset.ai/reference/api-overview)
- [OpenAPI](openapi/haystack-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/haystack-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/haystack-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/deepset-ai)
- [LinkedIn](https://www.linkedin.com/company/deepset)
- [Website](https://haystack.deepset.ai)
- [Documentation](https://docs.haystack.deepset.ai/docs/intro)
- [Plans](plans/haystack-ai-plans-pricing.yml)
- [Rate Limits](rate-limits/haystack-ai-rate-limits.yml)
- [Fin Ops](finops/haystack-ai-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
