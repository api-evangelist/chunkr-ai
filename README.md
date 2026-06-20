# Chunkr (chunkr-ai)

Chunkr is an open-source document intelligence platform that turns complex documents (PDF, Office, images) into RAG- and LLM-ready data. The Chunkr Cloud API at api.chunkr.ai performs layout analysis, OCR, segmentation, and chunking, and runs proprietary in-house vision models; the AGPL-3.0 open-source release (lumina-ai-inc/chunkr) can be self-hosted via Docker.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/chunkr-ai/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/chunkr-ai/refs/heads/main/apis.yml)

## Tags

- Document Parsing
- OCR
- Chunking
- RAG
- Document Intelligence

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Chunkr Parse Task API

Creates a parse task that runs layout analysis, OCR, segmentation, and chunking over an uploaded document, returning structured chunks, pages, and segment metadata with configurable chunk_processing, segment_processing, ocr_strategy, and segmentation_strategy.

- **Human URL:** [https://docs.chunkr.ai/api-references/tasks/create-parse-task](https://docs.chunkr.ai/api-references/tasks/create-parse-task)
- **Base URL:** `https://api.chunkr.ai`

#### Tags

- Parsing
- Layout Analysis
- Chunking

#### Properties

- [Documentation](https://docs.chunkr.ai/pages/get-started/welcome)
- [API Reference](https://docs.chunkr.ai/api-references/tasks/create-parse-task)
- [OpenAPI](openapi/chunkr-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/chunkr-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chunkr-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Chunkr Extract Task API

Creates an extract task that pulls schema-driven structured data from a document, returning JSON output with citations and metrics against a caller-supplied extraction schema and optional system prompt.

- **Human URL:** [https://docs.chunkr.ai/api-references/tasks/create-extract-task](https://docs.chunkr.ai/api-references/tasks/create-extract-task)
- **Base URL:** `https://api.chunkr.ai`

#### Tags

- Extraction
- Structured Output
- Schema

#### Properties

- [Documentation](https://docs.chunkr.ai/api-references/tasks/create-extract-task)
- [API Reference](https://docs.chunkr.ai/api-references/tasks/create-extract-task)
- [OpenAPI](openapi/chunkr-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/chunkr-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chunkr-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Chunkr Task Management API

Retrieves, lists, cancels, and deletes parse and extract tasks - get a task by id, get its parse or extract output, list tasks with pagination, cancel a running task, and delete a task and its artifacts.

- **Human URL:** [https://docs.chunkr.ai/api-references/tasks/get-task](https://docs.chunkr.ai/api-references/tasks/get-task)
- **Base URL:** `https://api.chunkr.ai`

#### Tags

- Tasks
- Polling
- Lifecycle

#### Properties

- [Documentation](https://docs.chunkr.ai/api-references/tasks/get-task)
- [API Reference](https://docs.chunkr.ai/api-references/tasks/get-task)
- [OpenAPI](openapi/chunkr-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/chunkr-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chunkr-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Chunkr Files API

Uploads, lists, retrieves, downloads, and deletes files that can be referenced by parse and extract tasks via ch://files/{file_id} references.

- **Human URL:** [https://docs.chunkr.ai/api-references/files/upload-a-file](https://docs.chunkr.ai/api-references/files/upload-a-file)
- **Base URL:** `https://api.chunkr.ai`

#### Tags

- Files
- Upload
- Storage

#### Properties

- [Documentation](https://docs.chunkr.ai/api-references/files/upload-a-file)
- [API Reference](https://docs.chunkr.ai/api-references/files/upload-a-file)
- [OpenAPI](openapi/chunkr-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/chunkr-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chunkr-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Chunkr Health and Extras API

Liveness health check and metadata helpers, including listing all supported file types accepted by the parsing and extraction pipelines.

- **Human URL:** [https://docs.chunkr.ai/api-references/health/health-check](https://docs.chunkr.ai/api-references/health/health-check)
- **Base URL:** `https://api.chunkr.ai`

#### Tags

- Health
- Utility
- Metadata

#### Properties

- [Documentation](https://docs.chunkr.ai/api-references/health/health-check)
- [API Reference](https://docs.chunkr.ai/api-references/health/health-check)
- [OpenAPI](openapi/chunkr-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/chunkr-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chunkr-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/lumina-ai-inc)
- [LinkedIn](https://www.linkedin.com/company/chunkr)
- [Website](https://chunkr.ai)
- [Documentation](https://docs.chunkr.ai)
- [Plans](plans/chunkr-ai-plans-pricing.yml)
- [Rate Limits](rate-limits/chunkr-ai-rate-limits.yml)
- [Fin Ops](finops/chunkr-ai-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
