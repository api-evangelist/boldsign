# BoldSign (boldsign)

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
