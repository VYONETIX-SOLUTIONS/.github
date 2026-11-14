# VYONETIX-SOLUTIONS

Headless developer data APIs for source-linked software risk checks and AI workload cost estimates.

## APIs

### AI Spend Guard

Estimate text-model workload costs from a source-attributed catalog, before deployment.

- [Open the RapidAPI listing and choose a plan](https://rapidapi.com/vyonetix-solutions-vyonetix-solutions-default/api/vyonetix-ai-spend-guard)
- Operations: `GET /v1/models/prices` and `POST /v1/workloads/estimate`
- [API documentation and examples](https://github.com/VYONETIX-SOLUTIONS/vyonetix-ai-spend-guard)
- [GitHub Actions budget-gate preview](https://github.com/VYONETIX-SOLUTIONS/vyonetix-ai-spend-guard-action)

The listing currently shows BASIC at $0 for 1,000 requests/month, PRO at $9.99 for 10,000, ULTRA at $29.99 for 100,000, and MEGA at $99.99 for 500,000. RapidAPI's current listing controls the actual limits, signup requirements, and charges. It may request a payment card even for a free plan and lists a 10,240 MB monthly bandwidth allowance with a charge for excess use. The API provides estimates, not runtime spend enforcement, provider invoices, model-quality equivalence, or guaranteed savings. The service is an early-access pilot without an SLA; consumers should verify their own gateway requests before relying on it.

### Developer Risk Signals

Normalize source-linked vulnerability and malicious-package evidence for developer workflows.

- [Open the RapidAPI listing](https://rapidapi.com/vyonetix-solutions-vyonetix-solutions-default/api/vyonetix-developer-risk-signals)
- Operations: `GET /v1/security/kev`, `POST /v1/dependencies/check`, and `POST /v1/packages/malicious-check`
- [Free timestamped sample, source notes, and integration examples](https://github.com/VYONETIX-SOLUTIONS/vyonetix-developer-risk-signals-demo)

The listing currently offers a free BASIC plan with a 1,000-request monthly quota. RapidAPI controls signup and card requirements. Results provide evidence to review; a match or no-match is not a safety verdict. Do not send confidential SBOMs or private package names. This is a controlled pilot without an SLA.

## Data and service principles

- Show provenance, licences, observation times, and freshness limits.
- Keep estimates reproducible and describe their exclusions.
- Protect credentials and avoid collecting prompts or private workload payloads.
- Treat marketplace listings and upstream source terms as authoritative for current availability and access.

Vyonetix API Signals: [Telegram](https://t.me/vyonetix_api_signals) · [Discord community invite](https://discord.gg/wNxCwSnZw)
