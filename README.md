# Freeplay (freeplay)

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
