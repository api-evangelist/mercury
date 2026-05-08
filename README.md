# Mercury (mercury)

Mercury is a banking platform built for startups and tech companies, offering checking, savings, treasury, and corporate-card services. The Mercury REST API exposes accounts, transactions, statements, recipients, ACH/wire payments, treasury yield, cards, and webhooks.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/mercury/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=mercury-api-evangelist&utm_content=repo)

## Type

- **x-type:** company

## Tags

- Banking, Fintech, Startups, Treasury, Payments

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

| API | Description |
|---|---|
| Mercury Accounts API | Read access to checking, savings, and treasury accounts on the organization. |
| Mercury Transactions API | Lists and retrieves transactions per account with filtering and pagination. |
| Mercury Statements API | Monthly account statements with downloadable PDF URLs. |
| Mercury Recipients API | Manages payment recipients (counterparties) for outbound ACH and wire payments. |
| Mercury Payments API | Sends outbound ACH and domestic wire payments; requires read-write tokens with IP allowlisting. |
| Mercury Cards API | Read access to corporate card metadata and spending limits. |
| Mercury Treasury API | Treasury account details, yield, and portfolio allocation. |
| Mercury Webhooks API | Signed event subscriptions for transactions, payments, and account events. |

## Common Properties

- [Website](https://mercury.com/)
- [Documentation](https://docs.mercury.com/)
- [Plans](plans/mercury-plans-pricing.yml) - API Commons Plans 0.1
- [RateLimits](rate-limits/mercury-rate-limits.yml) - API Commons Rate Limits 0.1
- [FinOps](finops/mercury-finops.yml) - FOCUS-aligned FinOps Framework 1.0

## Plans

- **Mercury (Free)** - $0/month; checking, savings, basic payments, basic invoicing, up to 5 reimbursement users, read API access.
- **Mercury Plus** - $35/month ($29.17/mo annual); recurring invoices, invoicing API capped at 500/mo, $1 per ACH invoice payment, up to 20 reimbursement users.
- **Mercury Pro** - $350/month ($291.67/mo annual); dedicated relationship manager, free ACH invoice payments, unlimited invoicing API, up to 250 reimbursement users, NetSuite integration.

## Rate Limits

- 429 Too Many Requests on per-token throttling (numeric ceiling not published).
- Plus tier: invoicing API capped at 500 invoices created per month.
- Read-write tokens are bound to a fixed IP allowlist.

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
