# Tangerine (tangerine)

Tangerine is a Canadian direct (branchless) bank headquartered in Toronto, Ontario, and a federally regulated Schedule I bank chartered as Tangerine Bank. Founded in 1997 as ING Direct Canada and acquired by Scotiabank in 2012 (rebranded to Tangerine in 2014), it operates as Scotiabank's digital-banking arm — a separate legal entity serving roughly two million clients with no-fee chequing and savings accounts, GICs, mortgages, mutual funds, and a cash-back Mastercard, delivered entirely through mobile and web.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/tangerine/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/tangerine/refs/heads/main/apis.yml)

## Open-Finance & API Posture

Tangerine publishes **no first-party public developer portal and no downloadable API specifications**. Probes of `developer.tangerine.ca` (no host) and `api.tangerine.ca` (HTTP 403, gated) confirm there is no public developer surface. As a Scotiabank subsidiary, Tangerine is a distinct entity from the Scotiabank parent, which runs its own commercial developer portal (developer.scotiabank.com) — that portal is **not** attributed here.

Canada has no operational open-banking / consumer-driven-banking (CDB) mandate today. The federal framework (Budget 2024 + Fall Economic Statement 2024, overseen by the Financial Consumer Agency of Canada) is legislated but not yet live, so access is voluntary and fragmented. For Tangerine, third-party access to client account and transaction data is therefore **aggregator-based** — via Plaid and Finicity (Mastercard) — rather than a documented first-party API. Tangerine supports Interac e-Transfer as a consumer payment feature (no public API), and in November 2025 announced a next-generation core-banking migration with Engine by Starling.

This repository is an identity-only (stub) profile: honest company identity plus the real, aggregator-only data-access posture. It will be updated if Tangerine publishes a first-party developer portal or API.

## Tags

- Financial Services
- Banking
- Canada
- Digital Bank
- Neobank
- Schedule I Bank
- Data Aggregation
- Interac

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

No first-party public APIs are documented. Client data access is available only through third-party aggregators (Plaid, Finicity/Mastercard).

## Common Properties

- [Website](https://www.tangerine.ca)
- [Terms of Service](https://www.tangerine.ca/en/legal)
- [Privacy Policy](https://www.tangerine.ca/en/privacy)
- [LinkedIn](https://ca.linkedin.com/company/tangerine-bank)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
