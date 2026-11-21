# Arlo Kharod

Software engineer based in Lafayette, Louisiana, currently seeking backend and full-stack roles (remote US or Lafayette area). From January 2025 through October 2026 I worked at [Adaptive Software LLC](https://adaptivesoftwarellc.com) on healthcare operations software: C#/.NET APIs, React and TypeScript front ends, SQL Server, and Azure. That production work lives in private repositories. My public projects explore backend design, data integrity, platform engineering and security.

## Projects

| | | |
|---|---|---|
| **[TomeStack](https://github.com/firegiant9000/TomeStack)** | Local-first Windows desktop app (.NET 10, WPF + WebView2, React/TypeScript, SQLite) for tabletop character rules. A pure C# rules engine that traces every calculated value to its rule and source, with the page where one is recorded; insert-only content revisions; and experimental PDF import with OCR into reviewable drafts. About 6,400 .NET tests and 2,000 UI unit tests run in CI; decisions are recorded as ADRs. | solo |
| **[FairTix](https://github.com/firegiant9000/FairTix)** | Concert ticketing under on-sale contention. Java 21 / Spring Boot 4, PostgreSQL, React. Pessimistic seat-row holds taken in sorted order to avoid deadlocks, advisory-lock purchase caps, an SSE waiting room, fraud scoring with reCAPTCHA step-up, signature-verified Stripe webhooks, OWASP Dependency-Check and Trivy in CI. Runs locally; never deployed. | six-person university team; primary author, continued solo |
| **[Hacker Tracker](https://github.com/firegiant9000/Senior-Cybersecurity-Project)** | Prototype threat-intelligence and asset-risk platform for small businesses: version-aware CPE→CVE matching with a CI calibration gate, KEV/EPSS prioritisation, and a read-only Go host agent for Linux with per-host tokens and replay protection. FastAPI, React, PostgreSQL. | six-person capstone; primary author, continued solo |
| **[PlanPal](https://github.com/firegiant9000/PlanPal)** | Calendar app with recurring events and per-occurrence changes, on Expo + Next.js + Supabase in a pnpm/Turborepo monorepo. Types generated from an OpenAPI contract and checked in CI, row-level security with grant and policy tests, deploy verification that fails on a no-op deploy. Friend sharing is planned, not built: the schema, a read policy and friend codes exist; request/accept flows and shared views do not. | two-person project, primary author; [web demo](https://planpal-iota.vercel.app) |
| **[Countersign](https://github.com/firegiant9000/CounterSign)** | Local-only Firefox extension that tracks job applications and fills application forms on a click. TypeScript, Preact, WXT. No network requests and no content scripts, enforced by lint rules, the CSP and tests on the built output. | solo; v1.0.0, built from source (not on the add-on store) |
| **[B.O.A.R.D](https://github.com/firegiant9000/B.O.A.R.D)** | Real-time collaborative whiteboard on Expo + Firebase. Plan limits enforced in Cloud Functions and rules, metered AI gateway, idempotent and ordered Stripe webhook handling. Frozen; not deployed. | course origin, solo continuation |

## How I work

Contract first, tests that fail for the right reason, and READMEs that say
what is actually built. Every repo above has a status section that is
honest about what is not done.

[Portfolio](https://firegiant9000.github.io/) · [LinkedIn](https://www.linkedin.com/in/arlo-k-16a618273/) · arlo.kharod@gmail.com
