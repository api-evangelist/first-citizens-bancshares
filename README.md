# First Citizens BancShares

This is a repository for tracking the APIs, SDKs, and other developer resources for First Citizens BancShares (FCB).

First Citizens BancShares is a super-regional financial holding company and the parent of First-Citizens Bank & Trust, providing general banking, trust, investment, insurance, and asset-management services.

## APIs

First Citizens does not operate a first-party developer portal on firstcitizens.com. Its real programmable surface comes through **Silicon Valley Bank (SVB)** — acquired in 2023 and now a division of First Citizens — whose Apigee-backed developer portal at [developer.svb.com](https://developer.svb.com) publishes a family of commercial banking REST APIs (base URL `https://api.svb.com`, OAuth2 + JSON Web Signature):

- **SVB Authorization API** — OAuth2 token issuance + JWS request signing
- **SVB Account Balance API** — real-time account balances
- **SVB Account Transfer API** — book transfers between own accounts
- **SVB ACH Transfers API** — domestic, verified, and IAT ACH (Plaid instant account verification)
- **SVB Instant Payments API** — real-time payments
- **SVB Wires API** — domestic and international wires
- **SVB Stop Payment API** — stop-check orders
- **SVB Virtual Cards API** — virtual card numbers for AP, procurement, travel
- **SVB Webhook API** — asynchronous event subscriptions
- **SVB Reference API** — instant-payments reachability look-ups

Access is partner-gated (commercial onboarding). Consumer account data on firstcitizens.com is reachable via the **Plaid** aggregator. No downloadable OpenAPI/Swagger is published — the portal renders an interactive reference client-side.

## Tags

- Banking
- Financial Services
- Commercial Banking
- Payments
- ACH
- Wire Transfers
- Virtual Cards
- Open Banking
- United States

## Properties

- [Website](https://www.firstcitizens.com)
- [Developer Portal (SVB)](https://developer.svb.com)
- [Documentation](https://developer.svb.com/apis/docs-home)
- [GitHub (SVB)](https://github.com/svb)
- [LinkedIn](https://www.linkedin.com/company/first-citizens-bank)
