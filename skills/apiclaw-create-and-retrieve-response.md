---
name: apiclaw-create-and-retrieve-response
description: Create a new response and then retrieve its details.
api: openapi/apiclaw.json
operations:
- responses_api_responses_post
- get_response_responses__response_id__get
generated: '2026-09-27'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/apiclaw.json ; every operationId checked against the contract
---

# apiclaw-create-and-retrieve-response

Create a new response and then retrieve its details.

## Steps

1. 1. `responses_api_responses_post` – send required request body fields as defined in the contract.
2. 2. `get_response_responses__response_id__get` – provide the `response_id` path parameter returned from the create call.

## Rules

- Include the API key in the `x-litellm-api-key` header (APIKeyHeader).
- The create operation is not idempotent; avoid duplicate calls.
