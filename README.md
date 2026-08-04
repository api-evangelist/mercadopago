# Mercado Pago (mercadopago)

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

Mercado Pago is the payments and financial-services arm of Mercado Libre, Latin America's largest e-commerce and fintech platform. Its developer portal at developers.mercadopago.com exposes a rich payments stack - Checkout Pro (hosted), Checkout Bricks (composable web components), Checkout API (full server-side control), Subscriptions, Payment Links, Point (in-person card reader), and QR payments - backed by REST APIs and official SDKs in Node.js, Python, PHP, Ruby, Java, .NET, plus a CLI and an MCP server for AI agents. Regional portals (.com.ar, .com.br, .com.mx, etc.) localise the docs and pricing per LATAM market.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/mercadopago/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/mercadopago/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Producer
- **Access:** 3rd-Party

## Tags

- Payments
- Checkout
- Subscriptions
- POS
- QR
- SDKs
- Latin America
- Brazil
- Argentina
- Mexico
- Fintech

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### Mercado Pago Payments API

Core REST API for creating and managing payments across cards, account-money, bank transfer (Pix in Brazil), boleto, and other LATAM methods. Supports capture, refund, partial refund, and status retrieval.

- **Human URL:** [https://www.mercadopago.com.ar/developers/en/reference/payments/_payments/post](https://www.mercadopago.com.ar/developers/en/reference/payments/_payments/post)
- **Base URL:** `https://api.mercadopago.com`

#### Tags

- Payments
- Checkout
- Refunds

#### Properties

- [Documentation](https://www.mercadopago.com.ar/developers/en/reference)
- [Postman Collection](collections/mercadopago.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercadopago.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mercado Pago Checkout Pro

Hosted, pre-configured checkout experience. Merchants create a preference via API, then redirect the buyer to the Mercado Pago hosted page that handles UI, payment-method selection, and 3DS, returning to a callback URL on completion.

- **Human URL:** [https://www.mercadopago.com.ar/developers/en/docs/checkout-pro/landing](https://www.mercadopago.com.ar/developers/en/docs/checkout-pro/landing)
- **Base URL:** `https://api.mercadopago.com`

#### Tags

- Checkout
- Hosted
- Preferences

#### Properties

- [Documentation](https://www.mercadopago.com.ar/developers/en/docs/checkout-pro/landing)
- [Postman Collection](collections/mercadopago.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercadopago.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mercado Pago Checkout Bricks

Composable web components ("bricks") that merchants embed in their own checkout UI - card form, wallet, payment-method picker, status screen. Lets merchants assemble a branded checkout while Mercado Pago handles PCI scope.

- **Human URL:** [https://www.mercadopago.com.ar/developers/en/docs/checkout-bricks/landing](https://www.mercadopago.com.ar/developers/en/docs/checkout-bricks/landing)
- **Base URL:** `https://api.mercadopago.com`

#### Tags

- Checkout
- Web Components
- Bricks

#### Properties

- [Documentation](https://www.mercadopago.com.ar/developers/en/docs/checkout-bricks/landing)
- [Postman Collection](collections/mercadopago.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercadopago.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mercado Pago Checkout API

Full server-side checkout control: tokenise cards client-side, create a payment server-side, manage 3DS challenges, and handle capture and refund - all without redirecting the buyer.

- **Human URL:** [https://www.mercadopago.com.ar/developers/en/docs/checkout-api/landing](https://www.mercadopago.com.ar/developers/en/docs/checkout-api/landing)
- **Base URL:** `https://api.mercadopago.com`

#### Tags

- Checkout
- Card Payments
- 3DS

#### Properties

- [Documentation](https://www.mercadopago.com.ar/developers/en/docs/checkout-api/landing)
- [Postman Collection](collections/mercadopago.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercadopago.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mercado Pago Subscriptions API

Recurring-payment subscriptions with scheduling, plans, free trial, proration, and pause / resume / cancel. Supports both subscription plans (shared) and per-customer pre-approved schedules.

- **Human URL:** [https://www.mercadopago.com.ar/developers/en/docs/subscriptions/landing](https://www.mercadopago.com.ar/developers/en/docs/subscriptions/landing)
- **Base URL:** `https://api.mercadopago.com`

#### Tags

- Subscriptions
- Recurring
- Plans

#### Properties

- [Documentation](https://www.mercadopago.com.ar/developers/en/docs/subscriptions/landing)
- [Postman Collection](collections/mercadopago.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercadopago.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mercado Pago Payment Links API

No-code / low-code link generation for collecting a one-off or recurring payment via shareable URL or button - SMS, WhatsApp, email, or social channels.

- **Human URL:** [https://www.mercadopago.com.ar/developers/en/docs/payment-link/landing](https://www.mercadopago.com.ar/developers/en/docs/payment-link/landing)
- **Base URL:** `https://api.mercadopago.com`

#### Tags

- Payment Links
- Collection

#### Properties

- [Documentation](https://www.mercadopago.com.ar/developers/en/docs/payment-link/landing)
- [Postman Collection](collections/mercadopago.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercadopago.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mercado Pago Point API (POS)

Integrates merchant systems with Mercado Pago Point card readers for in-person payments. Push an amount to a paired terminal, receive the authorization result, and reconcile via the same payment APIs.

- **Human URL:** [https://www.mercadopago.com.ar/developers/en/docs/mp-point/landing](https://www.mercadopago.com.ar/developers/en/docs/mp-point/landing)
- **Base URL:** `https://api.mercadopago.com`

#### Tags

- POS
- In Person
- Card Reader

#### Properties

- [Documentation](https://www.mercadopago.com.ar/developers/en/docs/mp-point/landing)
- [Postman Collection](collections/mercadopago.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercadopago.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mercado Pago QR API

Static and dynamic QR code APIs for in-person collection, with order-linked status retrieval and webhook callbacks.

- **Human URL:** [https://www.mercadopago.com.ar/developers/en/docs/qr-payments/landing](https://www.mercadopago.com.ar/developers/en/docs/qr-payments/landing)
- **Base URL:** `https://api.mercadopago.com`

#### Tags

- QR
- In Person
- Collections

#### Properties

- [Documentation](https://www.mercadopago.com.ar/developers/en/docs/qr-payments/landing)
- [Postman Collection](collections/mercadopago.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercadopago.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mercado Pago Webhooks / Notifications

Event-driven notifications for payments, refunds, chargebacks, subscriptions, and merchant-account changes. Webhooks are signed so receivers can verify authenticity.

- **Human URL:** [https://www.mercadopago.com.ar/developers/en/docs/your-integrations/notifications/webhooks](https://www.mercadopago.com.ar/developers/en/docs/your-integrations/notifications/webhooks)
- **Base URL:** `customer-configured`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://www.mercadopago.com.ar/developers/en/docs/your-integrations/notifications/webhooks)
- [Postman Collection](collections/mercadopago.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercadopago.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mercado Pago Node.js SDK

Official Node.js / TypeScript SDK wrapping the Mercado Pago REST APIs for payments, preferences, subscriptions, and merchant orders.

- **Human URL:** [https://github.com/mercadopago/sdk-nodejs](https://github.com/mercadopago/sdk-nodejs)
- **Base URL:** `https://github.com/mercadopago/sdk-nodejs`

#### Tags

- SDK
- Node.js
- TypeScript

#### Properties

- [Repository](https://github.com/mercadopago/sdk-nodejs)
- [Postman Collection](collections/mercadopago.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercadopago.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mercado Pago Python SDK

Official Python SDK wrapping the Mercado Pago REST APIs.

- **Human URL:** [https://github.com/mercadopago/sdk-python](https://github.com/mercadopago/sdk-python)
- **Base URL:** `https://github.com/mercadopago/sdk-python`

#### Tags

- SDK
- Python

#### Properties

- [Repository](https://github.com/mercadopago/sdk-python)
- [Postman Collection](collections/mercadopago.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercadopago.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mercado Pago PHP SDK

Official PHP SDK wrapping the Mercado Pago REST APIs.

- **Human URL:** [https://github.com/mercadopago/sdk-php](https://github.com/mercadopago/sdk-php)
- **Base URL:** `https://github.com/mercadopago/sdk-php`

#### Tags

- SDK
- PHP

#### Properties

- [Repository](https://github.com/mercadopago/sdk-php)
- [Postman Collection](collections/mercadopago.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercadopago.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mercado Pago Ruby SDK

Official Ruby SDK wrapping the Mercado Pago REST APIs.

- **Human URL:** [https://github.com/mercadopago/sdk-ruby](https://github.com/mercadopago/sdk-ruby)
- **Base URL:** `https://github.com/mercadopago/sdk-ruby`

#### Tags

- SDK
- Ruby

#### Properties

- [Repository](https://github.com/mercadopago/sdk-ruby)
- [Postman Collection](collections/mercadopago.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercadopago.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mercado Pago Java SDK

Official Java SDK wrapping the Mercado Pago REST APIs.

- **Human URL:** [https://github.com/mercadopago/sdk-java](https://github.com/mercadopago/sdk-java)
- **Base URL:** `https://github.com/mercadopago/sdk-java`

#### Tags

- SDK
- Java

#### Properties

- [Repository](https://github.com/mercadopago/sdk-java)
- [Postman Collection](collections/mercadopago.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercadopago.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mercado Pago .NET SDK

Official .NET / C# SDK wrapping the Mercado Pago REST APIs.

- **Human URL:** [https://github.com/mercadopago/sdk-dotnet](https://github.com/mercadopago/sdk-dotnet)
- **Base URL:** `https://github.com/mercadopago/sdk-dotnet`

#### Tags

- SDK
- .NET
- C#

#### Properties

- [Repository](https://github.com/mercadopago/sdk-dotnet)
- [Postman Collection](collections/mercadopago.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercadopago.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mercado Pago CLI

Command-line interface for managing Mercado Pago integrations, triggering test events, inspecting webhook deliveries, and scaffolding sample apps.

- **Human URL:** [https://www.mercadopago.com.ar/developers/en/docs/cli/landing](https://www.mercadopago.com.ar/developers/en/docs/cli/landing)
- **Base URL:** `https://www.mercadopago.com.ar/developers/en/docs/cli/landing`

#### Tags

- CLI
- Tooling
- DevEx

#### Properties

- [Documentation](https://www.mercadopago.com.ar/developers/en/docs/cli/landing)
- [Postman Collection](collections/mercadopago.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercadopago.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mercado Pago MCP Server

Model Context Protocol server that exposes Mercado Pago APIs as tools for AI agents and IDE assistants, enabling agent-driven payment and checkout workflows.

- **Human URL:** [https://www.mercadopago.com.ar/developers/en/docs/mcp-server/landing](https://www.mercadopago.com.ar/developers/en/docs/mcp-server/landing)
- **Base URL:** `https://www.mercadopago.com.ar/developers/en/docs/mcp-server/landing`

#### Tags

- MCP
- AI
- Agents

#### Properties

- [Documentation](https://www.mercadopago.com.ar/developers/en/docs/mcp-server/landing)
- [Postman Collection](collections/mercadopago.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercadopago.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.mercadopago.com/)
- [Developers](https://www.mercadopago.com.ar/developers/en)
- [Documentation](https://www.mercadopago.com.ar/developers/en/docs)
- [API Reference](https://www.mercadopago.com.ar/developers/en/reference)
- [LinkedIn](https://www.linkedin.com/company/mercadopago)
- [Git Hub](https://github.com/mercadopago)

## Maintainers

**FN:** API Evangelist
**URL:** https://apievangelist.com
