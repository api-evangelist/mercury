# Mercury

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Mercury is a banking platform built for startups and tech companies, offering checking, savings, treasury, and corporate-card services. The Mercury REST API exposes accounts, transactions, statements, recipients, ACH and wire payments, treasury yield, and webhooks.

**Areas:** Banking · Fintech · Startups · Treasury · Payments

## Mercury on APIs.io

Everything profiled for Mercury is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/mercury/](https://apis.io/providers/mercury/)** — or go straight to one of the APIs or properties below.

### APIs (16)

- [Mercury Accounts API](https://apis.io/apis/mercury/accounts/) — Read access to all Mercury accounts (checking, savings, treasury) opened under the authenticated organization. Returns account ID, name, type, status,…
- [Mercury Transactions API](https://apis.io/apis/mercury/transactions/) — Lists and retrieves transactions for a given Mercury account. Supports filtering by date range, status (pending, sent, cancelled, failed), and amount, plus…
- [Mercury Statements API](https://apis.io/apis/mercury/statements/) — Retrieves monthly account statements for a Mercury account. Each statement returns the start and end dates and a downloadable PDF URL.
- [Mercury Recipients API](https://apis.io/apis/mercury/recipients/) — Manages payment recipients (counterparties for outbound ACH and wire payments). Supports creating, retrieving, listing, updating, archiving, and approving…
- [Mercury Payments API](https://apis.io/apis/mercury/payments/) — Sends outbound ACH and domestic wire payments from a Mercury account to a recipient. Includes operations for requesting a send-money payment, retrieving its…
- [Mercury Cards API](https://apis.io/apis/mercury/cards/) — Read access to corporate card metadata - status, last four digits, the linked account, the card holder, and spending limits.
- [Mercury Treasury API](https://apis.io/apis/mercury/treasury/) — Surfaces treasury account details for organizations enrolled in Mercury Treasury, including yield, allocation across underlying money-market and Treasury…
- [Mercury Webhooks API](https://apis.io/apis/mercury/webhooks/) — Subscribes a partner application to event notifications such as transaction created/updated, payment status change, and account balance threshold events.…
- [Mercury Accounts API](https://apis.io/apis/mercury/mercury-accounts-api/) — The Accounts API from Mercury — 2 operation(s) for accounts.
- [Mercury Cards API](https://apis.io/apis/mercury/mercury-cards-api/) — The Cards API from Mercury — 1 operation(s) for cards.
- [Mercury Payments API](https://apis.io/apis/mercury/mercury-payments-api/) — The Payments API from Mercury — 2 operation(s) for payments.
- [Mercury Recipients API](https://apis.io/apis/mercury/mercury-recipients-api/) — The Recipients API from Mercury — 2 operation(s) for recipients.
- [Mercury Statements API](https://apis.io/apis/mercury/mercury-statements-api/) — The Statements API from Mercury — 1 operation(s) for statements.
- [Mercury Transactions API](https://apis.io/apis/mercury/mercury-transactions-api/) — The Transactions API from Mercury — 2 operation(s) for transactions.
- [Mercury Treasury API](https://apis.io/apis/mercury/mercury-treasury-api/) — The Treasury API from Mercury — 1 operation(s) for treasury.
- [Mercury Webhooks API](https://apis.io/apis/mercury/mercury-webhooks-api/) — The Webhooks API from Mercury — 2 operation(s) for webhooks.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Mercury Webhooks](https://apis.io/asyncapis/mercury/mercury-webhooks-asyncapi/)

#### Event channels (1)

Individual events and webhooks the provider emits.

- [/mercury/webhook](https://apis.io/channels/mercury/mercury-webhook/)

#### GraphQL (1)

GraphQL schemas.

- [Moved to /providers/mercury/](https://apis.io/graphqls/mercury/mercury-graphql/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [mercury](https://apis.io/servers/mercury/mercury/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Mercury Agentic Access](https://apis.io/agentic-access/mercury/mercury-agentic-access/)

#### Collections (9)

Postman and Open Collection request collections.

- [Mercury API](https://apis.io/collections/mercury/open-mercury/)
- [Mercury Accounts API](https://apis.io/collections/mercury/open-mercury-accounts-api/)
- [Mercury Accounts Cards API](https://apis.io/collections/mercury/open-mercury-cards-api/)
- [Mercury Accounts Payments API](https://apis.io/collections/mercury/open-mercury-payments-api/)
- [Mercury Accounts Recipients API](https://apis.io/collections/mercury/open-mercury-recipients-api/)
- [Mercury Accounts Statements API](https://apis.io/collections/mercury/open-mercury-statements-api/)
- [Mercury Accounts Transactions API](https://apis.io/collections/mercury/open-mercury-transactions-api/)
- [Mercury Accounts Treasury API](https://apis.io/collections/mercury/open-mercury-treasury-api/)
- [Mercury Accounts Webhooks API](https://apis.io/collections/mercury/open-mercury-webhooks-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Mercury — asyncapi rules](https://apis.io/rules/mercury/mercury-asyncapi-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Mercury Authentication](https://apis.io/security/mercury/mercury-authentication/)
- [Mercury Domain Security](https://apis.io/security/mercury/mercury-domain-security/)

#### Plans and pricing (2)

Published plans, tiers and prices.

- [Mercury Plans Pricing](https://apis.io/plans/mercury/mercury-plans-pricing/)
- [Mercury Price Estimates](https://apis.io/plans/mercury/mercury-price-estimates/)

#### Rate limits (1)

Published request limits.

- [Mercury Rate Limits](https://apis.io/rate-limits/mercury/mercury-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Mercury Finops](https://apis.io/finops/mercury/mercury-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://mercury.com/)
- [Documentation](https://docs.mercury.com/)
- [Getting started](https://docs.mercury.com/docs/getting-started)
- [Pricing](https://mercury.com/pricing)
- [Changelog](https://docs.mercury.com/changelog)
- [Blog](https://mercury.com/blog)
- [GitHub](https://github.com/MercuryTechnologies)

## API Evangelist rating

**Kin Score 38.8** — thin · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 75.0 |
| Contract quality | 56.9 |
| Contract governance | 13.6 |
| Operational transparency | 26.3 |
| Developer ergonomics | 29.8 |
| Access clarity | 42.1 |

**Agent readiness 30.8** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | verified |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | derived (partial credit) |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 9.4** — Banking & Open Finance

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/mercury/](https://apis.io/providers/mercury/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Mercury: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/mercury/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
