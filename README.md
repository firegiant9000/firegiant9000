# Arlo Kharod

Software engineer based in Lafayette, Louisiana, currently seeking backend and full-stack roles (remote US or Lafayette area). From January 2025 through October 2026 I worked at [Adaptive Software LLC](https://adaptivesoftwarellc.com) on healthcare operations software: C#/.NET APIs, React and TypeScript front ends, SQL Server, and Azure. That production work lives in private repositories. My public projects explore backend design, data integrity, platform engineering and security.

## Projects

| | | |
|---|---|---|
| **[TomeStack](https://github.com/firegiant9000/TomeStack)** | Local-first Windows desktop app (.NET 10, WPF + WebView2, React, SQLite) for tabletop character rules. A pure C# rules engine that traces every calculated value to its rule and source page, insert-only content revisions, and experimental PDF import with OCR into reviewable drafts. About 6,200 .NET tests and 2,000 UI tests run in CI; decisions are recorded as ADRs. | solo |
| **[Hacker Tracker](https://github.com/firegiant9000/Senior-Cybersecurity-Project)** | Threat-intelligence and asset-risk platform for SMBs: version-aware CPE→CVE matching with a CI calibration gate, KEV/EPSS prioritisation, a read-only Go host agent with per-host tokens and replay protection. FastAPI, React, PostgreSQL. | six-person capstone, lead author, continued solo |
| **[FairTix](https://github.com/firegiant9000/FairTix)** | Ticketing under on-sale contention. Java 21 / Spring Boot. PostgreSQL pessimistic seat holds with deadlock-safe ordering, advisory-lock purchase caps, SSE waiting room on Redis, fraud scoring with step-up auth, signature-verified Stripe webhooks, OWASP and Trivy in CI. Runs locally; never deployed. | six-person team project, lead author, continued solo |
| **[PlanPal](https://github.com/firegiant9000/PlanPal)** | Calendar with a one-way sharing layer. Expo + Next.js + Supabase monorepo. OpenAPI contract enforced in CI, row-level security with grant and policy tests, deploy verification that fails on a no-op deploy. | solo; [live demo](https://planpal-iota.vercel.app) |
| **[Countersign](https://github.com/firegiant9000/CounterSign)** | Local-only Firefox extension for tracking job applications. TypeScript, Preact, WXT. No network requests and no content scripts, enforced by lint rules, the CSP and tests on the built output. | solo; in development (v0.2.0) |
| **[B.O.A.R.D](https://github.com/firegiant9000/B.O.A.R.D)** | Real-time collaborative whiteboard on Expo + Firebase. Plan limits enforced in Cloud Functions and rules, metered AI gateway, idempotent and ordered Stripe webhook handling. Frozen; not deployed. | course origin, solo continuation |

## How I work

Contract first, tests that fail for the right reason, and READMEs that say
what is actually built. Every repo above has a status section that is
honest about what is not done.

[LinkedIn](https://www.linkedin.com/in/arlo-k-16a618273/) · arlo.kharod@gmail.com
