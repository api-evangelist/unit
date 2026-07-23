# Unit (unit)

Unit is a US Banking-as-a-Service (BaaS) platform that lets companies embed banking, cards, and payments into their own products. Its REST API spans Applications, Customers, Accounts (deposit/credit/wallet/DACA), Cards, Payments (book/ACH/wire/recurring/received/cash), Checks, Card Authorizations, Disputes, Transactions, Statements, Tax Forms, Fees & Rewards, Credit repayments, Stop Payments, and Webhooks. Authentication uses organization and customer bearer tokens, with idempotency keys and resource tagging built in.

Unit publishes a public OpenAPI 3.0.2 specification at https://github.com/unit-finance/openapi-unit-sdk (openapi.json, 117 paths) and generates official Node, Python, Ruby, and Java SDKs from it. The spec has been harvested verbatim and split into 16 per-resource-family OpenAPI files under `openapi/`. Endpoints documented at https://www.unit.co/docs/api.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/unit/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=unit-api-evangelist&utm_content=repo)

## Type
- **x-type:** company

## APIs
- **Unit Applications API** - Onboarding: individual/business applications, forms, KYC/KYB documents, beneficial owners.
- **Unit Customers API** - Customers, authorized/API users, archival, and customer-scoped tokens.
- **Unit Accounts API** - Deposit, credit, wallet (FBO) and DACA accounts, limits, and relationships.
- **Unit Cards API** - Card issuance, freeze/replace/report, limits, and secure PIN status.
- **Unit Payments API** - Book/ACH/wire, recurring, received, and cash deposits, counterparties, returns, institutions.
- **Unit Checks API** - Check payments (print-and-mail) and mobile check deposits.
- **Unit Card Authorizations API** - Real-time authorization requests (approve/decline) and authorizations.
- **Unit Disputes API** - Card transaction disputes and status.
- **Unit Transactions API** - Account transaction listing and retrieval.
- **Unit Statements API** - HTML/PDF and bank-branded statements.
- **Unit Tax Forms API** - Tax forms and PDF renderings.
- **Unit Fees and Rewards API** - Fee charge/reverse and rewards.
- **Unit Credit and Repayments API** - Repayments and recurring repayments.
- **Unit Stop Payments API** - Stop payments and positive-pay controls.
- **Unit Webhooks and Events API** - Webhook registration and the events Unit emits.
- **Unit Sandbox and Reference API** - Sandbox simulation endpoints and store/ATM location reference data.

## Tags
 - FinTech, BaaS, Banking, Payments, Card Issuing, ACH, United States, Embedded Finance, Deposit Accounts, Open Finance

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-07-23

## Common Properties
- [Website](https://www.unit.co/)
- [Plans](plans/unit-plans-pricing.yml)
- [RateLimits](rate-limits/unit-rate-limits.yml)
- [FinOps](finops/unit-finops.yml)

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
