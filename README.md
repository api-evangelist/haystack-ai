# Haystack / deepset (haystack-ai)

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
