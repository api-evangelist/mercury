# Mercury (mercury)

Mercury is a banking platform built for startups and tech companies, offering checking, savings, treasury, and corporate-card services. The Mercury REST API exposes accounts, transactions, statements, recipients, ACH and wire payments, treasury yield, and webhooks.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/mercury/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/mercury/refs/heads/main/apis.yml)

## Tags

- Banking
- Fintech
- Startups
- Treasury
- Payments

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-30

## APIs

### Mercury Accounts API

Read access to all Mercury accounts (checking, savings, treasury) opened under the authenticated organization. Returns account ID, name, type, status, current and available balances, account number, routing number, and account-holder details.

- **Human URL:** [https://docs.mercury.com/reference/accounts](https://docs.mercury.com/reference/accounts)
- **Base URL:** `https://api.mercury.com/api/v1`

#### Tags

- Accounts
- Banking
- Balance

#### Properties

- [Documentation](https://docs.mercury.com/reference/accounts)
- [Postman Collection](collections/mercury.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercury.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mercury Transactions API

Lists and retrieves transactions for a given Mercury account. Supports filtering by date range, status (pending, sent, cancelled, failed), and amount, plus pagination. Returns counterparty information, kind (ACH, wire, card, internal transfer, fee), category, note, and audit timestamps.

- **Human URL:** [https://docs.mercury.com/reference/transactions](https://docs.mercury.com/reference/transactions)
- **Base URL:** `https://api.mercury.com/api/v1`

#### Tags

- Transactions
- Reporting

#### Properties

- [Documentation](https://docs.mercury.com/reference/transactions)
- [Postman Collection](collections/mercury.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercury.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mercury Statements API

Retrieves monthly account statements for a Mercury account. Each statement returns the start and end dates and a downloadable PDF URL.

- **Human URL:** [https://docs.mercury.com/reference/get-statements](https://docs.mercury.com/reference/get-statements)
- **Base URL:** `https://api.mercury.com/api/v1`

#### Tags

- Statements
- Reporting
- PDF

#### Properties

- [Documentation](https://docs.mercury.com/reference/get-statements)
- [Postman Collection](collections/mercury.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercury.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mercury Recipients API

Manages payment recipients (counterparties for outbound ACH and wire payments). Supports creating, retrieving, listing, updating, archiving, and approving recipients. Read-and-write access to this endpoint requires IP whitelisting.

- **Human URL:** [https://docs.mercury.com/reference/recipients](https://docs.mercury.com/reference/recipients)
- **Base URL:** `https://api.mercury.com/api/v1`

#### Tags

- Recipients
- Counterparties
- Payments

#### Properties

- [Documentation](https://docs.mercury.com/reference/recipients)
- [Postman Collection](collections/mercury.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercury.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mercury Payments API

Sends outbound ACH and domestic wire payments from a Mercury account to a recipient. Includes operations for requesting a send-money payment, retrieving its status, and cancelling pending payments. Read-and-write tokens are required and must originate from a whitelisted IP.

- **Human URL:** [https://docs.mercury.com/reference/send-money](https://docs.mercury.com/reference/send-money)
- **Base URL:** `https://api.mercury.com/api/v1`

#### Tags

- Payments
- ACH
- Wire

#### Properties

- [Documentation](https://docs.mercury.com/reference/send-money)
- [Postman Collection](collections/mercury.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercury.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mercury Cards API

Read access to corporate card metadata - status, last four digits, the linked account, the card holder, and spending limits.

- **Human URL:** [https://docs.mercury.com/reference/cards](https://docs.mercury.com/reference/cards)
- **Base URL:** `https://api.mercury.com/api/v1`

#### Tags

- Cards
- Spending
- Corporate Cards

#### Properties

- [Documentation](https://docs.mercury.com/reference/cards)
- [Postman Collection](collections/mercury.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercury.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mercury Treasury API

Surfaces treasury account details for organizations enrolled in Mercury Treasury, including yield, allocation across underlying money-market and Treasury bill portfolios, and current balance.

- **Human URL:** [https://docs.mercury.com/reference/treasury](https://docs.mercury.com/reference/treasury)
- **Base URL:** `https://api.mercury.com/api/v1`

#### Tags

- Treasury
- Yield
- Cash Management

#### Properties

- [Documentation](https://docs.mercury.com/reference/treasury)
- [Postman Collection](collections/mercury.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercury.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mercury Webhooks API

Subscribes a partner application to event notifications such as transaction created/updated, payment status change, and account balance threshold events. Mercury signs each delivery so receivers can verify authenticity.

- **Human URL:** [https://docs.mercury.com/reference/webhooks](https://docs.mercury.com/reference/webhooks)
- **Base URL:** `https://api.mercury.com/api/v1`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://docs.mercury.com/reference/webhooks)
- [AsyncAPI](asyncapi/mercury-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/mercury.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercury.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/MercuryTechnologies)
- [LinkedIn](https://www.linkedin.com/company/mercuryhq)
- [Website](https://mercury.com/)
- [Documentation](https://docs.mercury.com/)
- [Plans](plans/mercury-plans-pricing.yml)
- [Rate Limits](rate-limits/mercury-rate-limits.yml)
- [Fin Ops](finops/mercury-finops.yml)
- [L L Ms Txt](https://docs.mercury.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
