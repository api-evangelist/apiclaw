---
name: apiclaw-billing-purchase-plan
description: Purchase a subscription plan by listing available plans and then checking out the selected plan.
api: openapi/apiclaw.json
operations:
- list_plans_billing_plans_get
- billing_checkout_billing_checkout_post
generated: '2026-09-27'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/apiclaw.json ; every operationId checked against the contract
---

# apiclaw-billing-purchase-plan

Purchase a subscription plan by listing available plans and then checking out the selected plan.

## Steps

1. 1. Retrieve the catalog of available plans using the operation `list_plans_billing_plans_get` (requires header `x-litellm-api-key`).
2. 2. Complete the purchase of a chosen plan with the operation `billing_checkout_billing_checkout_post` (requires header `x-litellm-api-key` and the checkout request body as defined in the contract).

## Rules

- Auth: Include the API key in the request header `x-litellm-api-key` for all calls.
