# USAA

USAA (United Services Automobile Association) is a Fortune 100 financial services group offering banking, investing, and insurance products to people and families that serve, or served, in the United States military. USAA is an active member of the Financial Data Exchange (FDX) and provides open banking data access through API aggregators.

**Website:** https://www.usaa.com  
**GitHub:** https://github.com/usaa  
**APIs.yml:** https://raw.githubusercontent.com/api-evangelist/usaa/refs/heads/main/apis.yml

---

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

Financial Services, Banking, Insurance, Military Finance, Open Banking, Fortune 100

## Timestamps

- **Created:** 2026-03-21
- **Modified:** 2026-05-03

---

## APIs

### Open Banking via Aggregators
USAA does not maintain a public developer portal, but supports member-permissioned data sharing through:

- **Plaid** — Account, balance, and transaction data for USAA members
- **Mastercard Open Banking (formerly Flinks)** — Account aggregation connectivity

USAA participates in the **Financial Data Exchange (FDX)** standard for secure open banking data sharing.

- **FDX Member Spotlight:** https://www.financialdataexchange.org/FDX/FDX/News/Spotlights/Member%20Spotlight%20USAA.aspx

### Open Source GitHub Projects
- [sonar-quality-gates](https://github.com/usaa/sonar-quality-gates) — Gradle plugin for Sonar quality gates
- [indexa](https://github.com/usaa/indexa) — Java dependency artifact analyzer
- [vogel](https://github.com/usaa/vogel) — Actuarial ML workflow tool
- [assemblyline-service-synapse](https://github.com/usaa/assemblyline-service-synapse) — Cyber threat intelligence integration

---

## Artifacts

| Type | Files |
|------|-------|
| JSON Schema | [json-schema/](json-schema/) — 2 schemas |
| JSON Structure | [json-structure/](json-structure/) — 1 structure |
| JSON-LD | [json-ld/](json-ld/) — 1 context |
| Vocabulary | [vocabulary/](vocabulary/) — 1 vocabulary |

---

## Open Banking Connectivity

USAA accounts are accessible through these aggregators for authorized third-party applications:

| Aggregator | Coverage |
|---|---|
| Plaid | Checking, savings, credit, investment accounts |
| Mastercard Open Banking | Checking, savings, credit accounts |

Data available through aggregators:
- Account balances (available and current)
- Transaction history
- Account metadata

---

## Use Cases

- **Personal Finance Management** — Integrate USAA accounts in budgeting apps
- **Account Aggregation** — View USAA accounts alongside other financial institutions
- **Military Family Financial Planning** — Leverage USAA's specialized military financial products
- **Open Banking Integration** — Access USAA data via FDX-aligned standards

---

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
