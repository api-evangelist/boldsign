# BoldSign (boldsign)

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

BoldSign is an e-signature platform built by Syncfusion that provides a REST API for sending documents for electronic signature, managing reusable templates, tracking envelope status, and embedding signing and requesting workflows directly into third-party applications. The API supports both API key and OAuth 2.0 authentication and outputs JSON responses across US, EU, CA, and AU regional endpoints. BoldSign offers official SDKs for .NET, Python, Java, Node.js, and PHP, along with a free sandbox environment and an interactive API Explorer. The platform is SOC 2 Type II, HIPAA, GDPR, and eIDAS compliant, and supports webhooks for real-time event notifications.

APIs.json: https://raw.githubusercontent.com/api-evangelist/boldsign/refs/heads/main/apis.yml

Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=boldsign-api-evangelist&utm_content=repo

## Tags

- E-Signature
- Electronic Signature
- Document Management
- Embedded Signing
- Webhooks
- Templates
- Identity Verification
- Compliance

## APIs

### BoldSign eSignature API

REST API for sending documents for signature, managing templates, embedding signing and requesting workflows, retrieving audit trails, prefilling form fields, configuring webhooks, and managing users and teams.

- Human URL: https://developers.boldsign.com/
- Base URL: https://api.boldsign.com
- OpenAPI: https://api.boldsign.com/swagger/index.html

## Plans / Rate Limits / FinOps

### Plans

BoldSign offers a hybrid pricing model across six tiers:

| Plan | Price | Envelopes |
|------|-------|-----------|
| Essential | Free | 25/month |
| Growth | $15/user/month | 50/user/month |
| Business | $25/user/month | Unlimited |
| Premium | $138/month | 250/month |
| Enterprise API | $30/month base | 40 included, $0.75/additional |
| Free Sandbox | Free | Testing only |

Full details: [plans/boldsign-plans-pricing.yml](plans/boldsign-plans-pricing.yml)

### Rate Limits

- Production: 2,000 requests per hour per account
- Sandbox: 50 requests per hour per account
- Rate limit scope: account level (not per OAuth app or user)
- Throttle response: HTTP 429 Too Many Requests
- Monitoring headers: X-RateLimit-Remaining, X-RateLimit-Reset

Full details: [rate-limits/boldsign-rate-limits.yml](rate-limits/boldsign-rate-limits.yml)

### FinOps

BoldSign uses a hybrid billing model. Subscription tiers cover fixed monthly envelope quotas; the Enterprise API plan adds metered per-envelope billing at $0.75/envelope once the 40-envelope monthly allocation is consumed. Draft envelopes are not charged; revocation of unsigned envelopes results in charge reversal.

Full details: [finops/boldsign-finops.yml](finops/boldsign-finops.yml)

## Timestamps

- Created: 2026-06-12
- Modified: 2026-06-12

## Common Properties

| Type | URL |
|------|-----|
| Website | https://boldsign.com/esignature-api/ |
| Documentation | https://developers.boldsign.com/ |
| GitHub Organization | https://github.com/boldsign |
| LinkedIn | https://www.linkedin.com/showcase/bold-sign-app/ |
| X (Twitter) | https://twitter.com/boldsignapp |
| Blog | https://boldsign.com/blogs/ |
| Pricing | https://boldsign.com/electronic-signature-pricing/ |
| Status Page | https://status.boldsign.com/ |
| Sandbox | https://developers.boldsign.com/api-overview/getting-started/ |

## Maintainers

- Kin Lane / kin@apievangelist.com
