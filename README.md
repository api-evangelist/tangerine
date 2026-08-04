# Tangerine (tangerine)

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
