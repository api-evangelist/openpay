# Openpay (openpay)

Openpay is a Mexican and Colombian online payments platform, part of the BBVA group, offering a REST API for accepting card payments, cash/store payments, and bank transfers (SPEI). The API covers charges, customers, cards, tokens, subscriptions, plans, payouts, transfers, fees, and webhooks under a per-merchant base path with HTTP Basic authentication using a private API key.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/openpay/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/openpay/refs/heads/main/apis.yml)

## Tags

- Payments
- Fintech
- Cards
- SPEI
- Subscriptions

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Openpay Charges API

Create and manage charges against cards, convenience stores (cash), and banks (SPEI) at both merchant and customer level, including capture, refund, and listing of transactions.

- **Human URL:** [https://documents.openpay.mx/docs/api](https://documents.openpay.mx/docs/api)
- **Base URL:** `https://api.openpay.mx/v1`

#### Tags

- Charges
- Payments
- Cards
- Store
- SPEI

#### Properties

- [Documentation](https://documents.openpay.mx/docs/api)
- [API Reference](https://documents.openpay.mx/docs/api)
- [OpenAPI](openapi/openpay-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/openpay.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openpay.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Openpay Customers and Cards API

Create, retrieve, update, list, and delete customers, store and manage their cards at merchant or customer level, and tokenize card data client-side to reduce PCI scope.

- **Human URL:** [https://documents.openpay.mx/docs/api](https://documents.openpay.mx/docs/api)
- **Base URL:** `https://api.openpay.mx/v1`

#### Tags

- Customers
- Cards
- Tokens
- Vault

#### Properties

- [Documentation](https://documents.openpay.mx/docs/api)
- [API Reference](https://documents.openpay.mx/docs/api)
- [OpenAPI](openapi/openpay-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/openpay.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openpay.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Openpay Subscriptions and Plans API

Define plans as templates for recurring charges (amount and frequency) and associate customers and cards to those plans through subscriptions, with full create, update, cancel, and list operations.

- **Human URL:** [https://documents.openpay.mx/docs/api](https://documents.openpay.mx/docs/api)
- **Base URL:** `https://api.openpay.mx/v1`

#### Tags

- Subscriptions
- Plans
- Recurring
- Billing

#### Properties

- [Documentation](https://documents.openpay.mx/docs/api)
- [API Reference](https://documents.openpay.mx/docs/api)
- [OpenAPI](openapi/openpay-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/openpay.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openpay.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Openpay Payouts and Transfers API

Send payouts to registered bank accounts, move funds between customers with transfers, and manage customer bank accounts used as payout destinations.

- **Human URL:** [https://documents.openpay.mx/docs/api](https://documents.openpay.mx/docs/api)
- **Base URL:** `https://api.openpay.mx/v1`

#### Tags

- Payouts
- Transfers
- Bank Accounts
- SPEI

#### Properties

- [Documentation](https://documents.openpay.mx/docs/api)
- [API Reference](https://documents.openpay.mx/docs/api)
- [OpenAPI](openapi/openpay-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/openpay.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openpay.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Openpay Fees API

Charge commission fees to a customer's Openpay balance, typically used in marketplace and split-payment scenarios, and list previously collected fees.

- **Human URL:** [https://documents.openpay.mx/docs/api](https://documents.openpay.mx/docs/api)
- **Base URL:** `https://api.openpay.mx/v1`

#### Tags

- Fees
- Commissions
- Marketplace

#### Properties

- [Documentation](https://documents.openpay.mx/docs/api)
- [API Reference](https://documents.openpay.mx/docs/api)
- [OpenAPI](openapi/openpay-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/openpay.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openpay.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Openpay Webhooks API

Register, verify, retrieve, list, and delete webhook endpoints that receive POST notifications for transaction events such as charge.succeeded, charge.refunded, charge.failed, and payout events.

- **Human URL:** [https://documents.openpay.mx/docs/webhooks.html](https://documents.openpay.mx/docs/webhooks.html)
- **Base URL:** `https://api.openpay.mx/v1`

#### Tags

- Webhooks
- Notifications
- Events

#### Properties

- [Documentation](https://documents.openpay.mx/docs/webhooks.html)
- [API Reference](https://documents.openpay.mx/docs/api)
- [OpenAPI](openapi/openpay-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/openpay.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openpay.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/open-pay)
- [LinkedIn](https://www.linkedin.com/company/openpay)
- [Website](https://www.openpay.mx)
- [Documentation](https://documents.openpay.mx/docs/api)
- [Plans](plans/openpay-plans-pricing.yml)
- [Rate Limits](rate-limits/openpay-rate-limits.yml)
- [Fin Ops](finops/openpay-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
