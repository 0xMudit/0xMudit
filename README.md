# Muditya Raghav

**Software Engineer · Backend, Systems & Full-Stack**

> I build production systems end to end, in public. Open to **remote software engineering roles** — immediate joiner.

<sup>I work across the whole stack of a product: data model, API, auth, background jobs, deployment, and the failure modes nobody wants to think about. A QA and security background left me permanently suspicious — so I design systems the way an attacker would read them, and ship them with the tests and documentation to prove they hold up.</sup>

[![Portfolio](https://img.shields.io/badge/Portfolio-mudityaraghav.vercel.app-black?style=flat-square)](https://mudityaraghav.vercel.app)
[![Résumé](https://img.shields.io/badge/Résumé-PDF-orange?style=flat-square)](https://mudityaraghav.vercel.app/assets/MudityaRaghav-Software-Engineer-Resume.pdf)
[![Book a call](https://img.shields.io/badge/Book_a_call-cal.com-green?style=flat-square)](https://cal.com/muditya-raghav-ai/60-min-meeting)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0xMudit-0A66C2?style=flat-square)](https://www.linkedin.com/in/0xmudit/)
[![Email](https://img.shields.io/badge/Email-mudityadev@gmail.com-white?style=flat-square)](mailto:mudityadev@gmail.com)

---

## Flagship systems

Open source, deployed, and documented. The live links are real deployments — click them.

| Project | What it does | Stack | Live |
|---|---|---|---|
| [**Red Sky**](https://github.com/0xMudit/redsky-agents) | Grok Bot–style AI teammates that run on your own machine — a desktop shell around a locally spawned OpenCode server. Each agent owns its session, sandboxed workspace, durable memory, and cron routines. Auto Review holds destructive, expensive, or outbound work for human approval, and every finished run reports the tools it ran, the files it touched, and a workspace diff | `Electron` `React 19` `TypeScript` `OpenCode` `Vite` `Tailwind 4` | [source](https://github.com/0xMudit/redsky-agents) |
| [**Clara Network**](https://github.com/0xMudit/clara-card-network) | A Mastercard/Visa-style card payment network built end to end: scheme routing, an ISO 8583 authorization switch, an append-only double-entry ledger with reconciliation, EMV/ARQC verification, a token vault, a disputes engine, HSM key management, and 24/7 ISO 20022 instant settlement | `Go` `ISO 8583/20022` `PostgreSQL` `Redis` `Docker` `HSM` `EMV` | [console](https://clara-network.vercel.app) |
| [**Malcom**](https://github.com/0xMudit/malcom-research-assistant) | AI research workspace — streamed LLM responses, document-context retrieval, web research with cited sources, saved chats, and Stripe-backed subscriptions | `Next.js` `TypeScript` `Supabase` `Stripe` `RAG` | [app](https://malcom-lake.vercel.app) |
| [**Kingswork**](https://github.com/0xMudit/kingswork-trading-platform) | Trading intelligence platform — market dashboards, backtesting, paper portfolios, and real-time alerts over JWT auth and WebSockets | `FastAPI` `React` `WebSockets` `SQLAlchemy` `JWT` | [app](https://kingswork-ruddy.vercel.app) |
| [**Jini**](https://github.com/0xMudit/jini-document-intelligence) | Local-first document intelligence — PDFs, spreadsheets, and invoices into searchable, cited answers. Ranked retrieval runs with **no API key**, so the default workflow stays private and self-contained | `React` `TypeScript` `Express` `SQLite` `Docker` | [demo](https://jini-document-intelligence.vercel.app) |

![Red Sky — agents on the left rail, a live run streaming into the workspace on the right](https://raw.githubusercontent.com/0xMudit/redsky-agents/main/docs/screenshots/dashboard.png)

<sub>*Red Sky — every agent gets a session, a sandboxed workspace, memory, and a schedule. It is the project I have shipped most carefully: MIT-licensed, documented in full, CI-gated, and carrying a public backlog of 131 labelled issues.*</sub>

## Also shipping

| Project | What it does | Stack | Live |
|---|---|---|---|
| [**Portfolio source**](https://github.com/0xMudit/portfolio-site) | The Next.js App Router source behind the site linked above — one typed data module drives every page | `Next.js` `TypeScript` `Tailwind v4` | [site](https://mudityaraghav.vercel.app) |

## Open source contributions

Fixes and features opened against upstream projects I depend on — each link is the actual pull request, not a fork I sat on.

**21 pull requests across 8 upstream projects** — 1 merged into OpenCV, 15 open, 5 closed.

| Project | Contribution | State |
|---|---|---|
| [OpenCV](https://github.com/opencv/opencv) | [#29981](https://github.com/opencv/opencv/pull/29981) — doc: document the bit layout of `Mat::type()` | **merged** |
| [OpenCV](https://github.com/opencv/opencv) | [#30015](https://github.com/opencv/opencv/pull/30015) — core: fix memory leak in `cv::glob()` on WinRT/_WIN32_WCE | open |
| [OpenCV](https://github.com/opencv/opencv) | [#29999](https://github.com/opencv/opencv/pull/29999) — core: hal: add `v_select` support for 64-bit integer types | open |
| [OpenCV](https://github.com/opencv/opencv) | [#29994](https://github.com/opencv/opencv/pull/29994) — core: fix `convertTo()` saturation for 64-bit and 32U sources on the vectorized path | open |
| [OpenCV](https://github.com/opencv/opencv) | [#29992](https://github.com/opencv/opencv/pull/29992) — test: pin cameraMatrix/newCameraMatrix order in `initInverseRectificationMap` | open |
| [OpenCV](https://github.com/opencv/opencv) | [#29982](https://github.com/opencv/opencv/pull/29982) — doc: add 5.x specific changes for Mat, MatShape, and 0d/1d Mat | open |
| [OpenCV](https://github.com/opencv/opencv) | [#29980](https://github.com/opencv/opencv/pull/29980) — doc: correct camera matrix order in `initInverseRectificationMap` description | open |
| [OpenCV](https://github.com/opencv/opencv) | [#29979](https://github.com/opencv/opencv/pull/29979) — doc: fix broken opencv.js link in the JS usage tutorial | open |
| [Sentry](https://github.com/getsentry/sentry) | [#125004](https://github.com/getsentry/sentry/pull/125004) — fix(releases): normalize trailing slash in project URL param | open |
| [peated](https://github.com/dcramer/peated) | [#1294](https://github.com/dcramer/peated/pull/1294) — feat(series): add aggregate rating to Series pages | open |
| [peated](https://github.com/dcramer/peated) | [#1293](https://github.com/dcramer/peated/pull/1293) — feat(web): tint bottle preview with selected pour color | open |
| [ToolJet](https://github.com/ToolJet/ToolJet) | [#17690](https://github.com/ToolJet/ToolJet/pull/17690) — fix: cloning an app with a custom data source fails with 422 | open |
| [ToolJet](https://github.com/ToolJet/ToolJet) | [#17683](https://github.com/ToolJet/ToolJet/pull/17683) — fix: install-page plugin card size and upgrade-button hover visibility | open |
| [Apache Maka](https://github.com/apache/maka) | [#3812](https://github.com/apache/maka/pull/3812) — fix(runtime): honor `isRetryable` in the provider retry classifier | open |
| [Apache Maka](https://github.com/apache/maka) | [#3810](https://github.com/apache/maka/pull/3810) — feat(ci): add self-assign issue workflow | open |
| [NetBird docs](https://github.com/netbirdio/docs) | [#946](https://github.com/netbirdio/docs/pull/946) — docs: forward UDP 443 for QUIC in external relay setup | open |
| [Apache Maka](https://github.com/apache/maka) | [#3809](https://github.com/apache/maka/pull/3809) — fix(deps): resolve npm audit vulnerabilities | closed |
| [PostHog](https://github.com/PostHog/posthog) | [#89642](https://github.com/PostHog/posthog/pull/89642) — feat(desktop): add configurable branch prefix setting | closed |
| [PostHog](https://github.com/PostHog/posthog) | [#89557](https://github.com/PostHog/posthog/pull/89557) — feat(desktop): group MCP tools by read/write category in tool lists | closed |
| [humanish](https://github.com/danielgwilson/humanish) | [#203](https://github.com/danielgwilson/humanish/pull/203) — feat: deterministic PII/PHI redaction gate | closed |
| [humanish](https://github.com/danielgwilson/humanish) | [#202](https://github.com/danielgwilson/humanish/pull/202) — docs: add state-driven local-app example | closed |

## Career record

Outcomes from employment and published research — not GitHub metrics.

| Metric | Result |
|---|---|
| AI-assisted test automation @ Reliance Jio | 80+ test cases, **+40% coverage** |
| API defect triage | 35+ critical bugs fixed, **+25% stability** |
| Jenkins CI/CD pipeline | **20% faster** release cadence |
| Python/Pandas QA automation | **90% less** repetitive QA time |
| Bug bounty (Cisco internship / HackerOne) | **3 verified** reports to PayPal |
| Published research | 2 papers — payment systems and low-light activity detection |

## How I work

- **Own the whole lifecycle.** Every project above went from an ambiguous idea to a deployed system — architecture, backend, frontend, CI, and operations are all mine.
- **Ship in public.** Open source, MIT-licensed where it applies, with architecture docs and READMEs written for a stranger who has to run it.
- **Contribute upstream.** When a dependency is wrong, I fix it in the upstream repository instead of working around it locally.
- **Reliability-first.** I design against auth bypass, injection, failure modes, and data correctness *before* the happy path — the security background is a permanent feature.
- **Measure, don't guess.** Systems get instrumented and CI-gated; quality is a number, not a vibe.
- **Write it down.** If a decision isn't documented, it isn't finished.

## Toolkit

**Languages** — Python · TypeScript · JavaScript · Go · SQL
**Backend** — FastAPI · Express · Next.js · Fastify · REST · WebSockets · SQLAlchemy · Celery
**Systems** — Docker · Linux · AWS EC2 · CI/CD · PostgreSQL · SQLite · MongoDB · Redis · Supabase
**Domain** — ISO 8583 · ISO 20022 · Double-entry ledgers · HSM/EMV · JWT auth · Stripe billing
**ML** — PyTorch · OSNet · ViT · YOLOv8 · HuggingFace
**Desktop / Agent runtimes** — Electron · Vite · esbuild · node:test · OpenCode · stdio tool protocols
**QA / SDET** — Selenium · Cypress · Playwright · Postman · Jenkins
**Security** — Burp Suite · Nmap · Wireshark · DVWA · Juice Shop

## Experience

| Role | Company | Period |
|---|---|---|
| Software Engineer (Independent) | Personal Engineering Practice | Apr 2025 – Present |
| QA Associate Engineer | Reliance Jio Platforms | Dec 2023 – Mar 2025 |
| Software Engineer Intern | Persistent Systems | Apr 2022 – Jun 2022 |
| Cyber Security Intern | Cisco Network | Apr 2021 – Jul 2021 |

B.Tech, Gyan Ganga Institute of Technology and Sciences (2019–2023) — CGPA 9.02/10.

## Find me

[Portfolio](https://mudityaraghav.vercel.app) · Résumé: [PDF](https://mudityaraghav.vercel.app/assets/MudityaRaghav-Software-Engineer-Resume.pdf) · X: [@0xMudit](https://twitter.com/0xMudit) · LinkedIn: [0xmudit](https://www.linkedin.com/in/0xmudit/) · HackerOne: [0xmudit](https://hackerone.com/0xmudit) · HuggingFace: [0xmudit](https://huggingface.co/0xmudit) · Live chat: [cal.com/muditya-raghav-ai](https://cal.com/muditya-raghav-ai/60-min-meeting) · Email: [mudityadev@gmail.com](mailto:mudityadev@gmail.com)
