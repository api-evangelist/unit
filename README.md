# Unit (unit)

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
