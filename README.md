# Flagstar (flagstar)

Flagstar Bank, N.A. is the OCC-chartered national bank subsidiary of Flagstar Financial, Inc. (NYSE: FLG), the Hicksville, New York holding company formerly known as New York Community Bancorp (NYCB). It is one of the largest regional (super-regional) banks in the United States. Flagstar runs a first-party developer portal at developer.flagstar.com, but as of this review it publishes no public, self-serve API products, documentation, or downloadable OpenAPI specs to anonymous visitors — all products are sign-in gated.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/flagstar/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/flagstar/refs/heads/main/apis.yml)

## Tags

- Financial Services
- Banking
- United States
- National Bank
- Super-Regional Bank
- Mortgage
- Open Finance
- Data Aggregation

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

No public, self-serve APIs are documented. Flagstar operates a first-party developer portal (a Broadcom/Layer7 "LivePortal" API Developer Portal) at [developer.flagstar.com](https://developer.flagstar.com), which returns HTTP 200 and presents "Products" and "Sign In" navigation. However, its public API-product catalog endpoint returns an empty set (`apiDocs: []`, `apiProducts: []`, `apiCategoryList: []`) — every product is gated behind authentication (partner/consumer-team access). No downloadable OpenAPI/Swagger is publicly available.

### Open-finance posture

- **First-party public API:** None. Developer portal exists but exposes zero public API products or specs to anonymous visitors.
- **FDX (Financial Data Exchange):** No publicly documented participation.
- **CFPB Section 1033:** No publicly documented data-access posture.
- **Aggregator access:** Consumer-permissioned data appears to be available only through third-party aggregators (e.g. Plaid, Tink, TrueLayer), not a first-party public API.

## Common Properties

- [Website](https://www.flagstar.com)
- [Developer Portal](https://developer.flagstar.com)
- [LinkedIn](https://www.linkedin.com/company/flagstar-bank)
- [Privacy Policy](https://www.flagstar.com/legal-disclaimers/privacy.html)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
