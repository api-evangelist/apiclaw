---
name: apiclaw-customer-management
description: Manage the lifecycle of a customer including creation, retrieval, update, blocking, unblocking, listing, and deletion.
api: openapi/apiclaw.json
operations:
- new_end_user_customer_new_post
- end_user_info_customer_info_get
- update_end_user_customer_update_post
- block_user_customer_block_post
- unblock_user_customer_unblock_post
- delete_end_user_customer_delete_post
generated: '2026-09-27'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/apiclaw.json ; every operationId checked against the contract
---

# apiclaw-customer-management

Manage the lifecycle of a customer including creation, retrieval, update, blocking, unblocking, listing, and deletion.

## Steps

1. 1. `new_end_user_customer_new_post` – requires the request body fields for the new end user.
2. 2. `end_user_info_customer_info_get` – requires the query parameter or header that identifies the customer (as defined in the contract).
3. 3. `update_end_user_customer_update_post` – requires the request body fields for updating the end user.
4. 4. `block_user_customer_block_post` – requires the request body fields to specify the user to block.
5. 5. `unblock_user_customer_unblock_post` – requires the request body fields to specify the user to unblock.
6. 6. `delete_end_user_customer_delete_post` – requires the request body fields to specify the user to delete.

## Rules

- Auth: Include the API key in the `x-litellm-api-key` header (scheme APIKeyHeader).
