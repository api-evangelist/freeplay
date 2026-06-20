# Freeplay (freeplay)

Freeplay is an LLM product experimentation, evaluation, and observability platform for cross-functional teams. Its HTTP API and SDKs make Freeplay the source of truth for prompt templates, record completions and sessions/traces from production, curate test datasets, run batch test runs and LLM-judge evaluations, and capture human and customer feedback.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/freeplay/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/freeplay/refs/heads/main/apis.yml)

## Tags

- AI
- LLM
- Evaluation
- Observability
- Prompt Management
- Experimentation

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Freeplay Prompt Templates API

Manage versioned prompt templates as the source of truth for an application, including creating templates and versions, retrieving formatted or raw templates by name or ID, deploying versions to environments, and listing all templates in an environment.

- **Human URL:** [https://docs.freeplay.ai/developer-resources/api-reference](https://docs.freeplay.ai/developer-resources/api-reference)
- **Base URL:** `https://app.freeplay.ai/api/v2`

#### Tags

- Prompt Management
- Templates
- Versioning

#### Properties

- [Documentation](https://docs.freeplay.ai/docs/freeplay-sdk)
- [API Reference](https://docs.freeplay.ai/developer-resources/api-reference)
- [OpenAPI](openapi/freeplay-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/freeplay.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/freeplay.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Freeplay Recordings & Sessions API

Record LLM completions back to Freeplay along with the sessions and traces that group related calls for agent workflows, then list, search, and delete sessions and aggregate completion statistics for production observability.

- **Human URL:** [https://docs.freeplay.ai/developer-resources/api-reference](https://docs.freeplay.ai/developer-resources/api-reference)
- **Base URL:** `https://app.freeplay.ai/api/v2`

#### Tags

- Recordings
- Sessions
- Traces
- Observability

#### Properties

- [Documentation](https://docs.freeplay.ai/getting-started/integrate)
- [API Reference](https://docs.freeplay.ai/developer-resources/api-reference)
- [OpenAPI](openapi/freeplay-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/freeplay.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/freeplay.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Freeplay Test Cases & Datasets API

Curate evaluation datasets and their test cases, retrieving dataset metadata and test cases by name or ID and uploading new test cases for use in batch test runs and experiments.

- **Human URL:** [https://docs.freeplay.ai/developer-resources/api-reference](https://docs.freeplay.ai/developer-resources/api-reference)
- **Base URL:** `https://app.freeplay.ai/api/v2`

#### Tags

- Datasets
- Test Cases
- Curation

#### Properties

- [Documentation](https://docs.freeplay.ai/docs/quick-start)
- [API Reference](https://docs.freeplay.ai/developer-resources/api-reference)
- [OpenAPI](openapi/freeplay-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/freeplay.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/freeplay.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Freeplay Test Runs & Evaluations API

Run batch evaluations against datasets, create and list test runs and retrieve their results, and record completion-level and trace-level customer and human feedback to close the evaluation feedback loop.

- **Human URL:** [https://docs.freeplay.ai/developer-resources/api-reference](https://docs.freeplay.ai/developer-resources/api-reference)
- **Base URL:** `https://app.freeplay.ai/api/v2`

#### Tags

- Evaluations
- Test Runs
- Feedback

#### Properties

- [Documentation](https://freeplay.ai/blog/llm-evaluation)
- [API Reference](https://docs.freeplay.ai/developer-resources/api-reference)
- [OpenAPI](openapi/freeplay-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/freeplay.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/freeplay.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/freeplayai)
- [LinkedIn](https://www.linkedin.com/company/freeplay-ai)
- [Website](https://freeplay.ai/)
- [Documentation](https://docs.freeplay.ai/)
- [Plans](plans/freeplay-plans-pricing.yml)
- [Rate Limits](rate-limits/freeplay-rate-limits.yml)
- [Fin Ops](finops/freeplay-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
