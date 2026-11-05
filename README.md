# Holden Richard

Computer Science at the University of Vermont (B.S. 2027, M.S. Complex Systems and Data Science 2028). Spending this semester at Auckland University of Technology in New Zealand.

I build things and then keep score on them. Most of the code in my iOS app was written with an AI coding agent, and the interesting problem turned out to be everything around that: how you stay accountable for what ships when you did not type it, which mistakes a machine can catch before they land, and which ones still need a person. That is what my research is about, and it is what most of the repos below are for.

### Flagship Testbed & Research Telemetry

**[Kabu](https://github.com/HoldenRichard/Kabu)** ([learnkabu.com](https://www.learnkabu.com/)) is a gamified iOS stock-market education app built solo under my LLC and currently in App Store review. It features 25 quiz-gated lessons, 4 historical market simulations, a 100-ticker S&P 500 paper-trading sandbox, and an end-to-end StoreKit 2 / App Store Server API JWS validation stack (~800ms in production).

Because the app source is private, the public repo serves as the architectural case study and hosts the telemetry from my semester-long AI engineering study ([holdenrichard.com](https://www.holdenrichard.com/)):

| Metric | Count | Verification Scope |
| :--- | :--- | :--- |
| **Logged Agent Sessions** | 171 | Structured prompt turns, review loops, and multi-agent handoffs |
| **Defect & Near-Miss Ledger** | 628 | 280 defects and 348 near-misses logged across 18 fields at detection turn |
| **Enforced Rules & CI Gates** | 49 | Repeat failure modes codified into repo rules and automated CI checks |
| **Attestation Promises** | 6 | Privacy, policy, and App Store label claims audited against live behavior |
| **Automated Test Suite** | 419 | Unit, regression, and StoreKit 2 / Firestore security rule verification |

---

### AI Agent Governance & Research

| Project | Focus | Stack | Proof / Signal |
| :--- | :--- | :--- | :--- |
| **[caselaw](https://github.com/HoldenRichard/caselaw)** [![npm](https://img.shields.io/npm/v/caselaw.svg?color=24292e&label=npm)](https://www.npmjs.com/package/caselaw) | Repo-specific verification guardrails enforced via Claude Code hooks (`npx caselaw`) | JavaScript, npm, Shell | Every rule carries a positive control proving it fails on bad input |
| **[governance-research-regime](https://github.com/HoldenRichard/governance-research-regime)** | Logging protocol: session logs, defect ledger, attestation register, CI gate | Python, GitHub Actions | 6-promise attestation register; protocol powering the 171-session AUT study |
| **[self-taught-operator](https://github.com/HoldenRichard/self-taught-operator)** | Continual-learning agent that teaches itself NandGame and compiles reusable skills | Python, Gemini Computer Use, Playwright, MongoDB Atlas, Voyage AI | Beat 5/5 tested levels across repeated loop runs (AIEWF Hackathon 2026) |

### Shipped Software & Systems

| Project | Focus | Stack | Proof / Signal |
| :--- | :--- | :--- | :--- |
| **[Kabu](https://github.com/HoldenRichard/Kabu)** | iOS investing education app case study and multi-agent engineering workflow | Swift, SwiftUI, Firebase, StoreKit 2 | 30+ TestFlight testers; App Store submission ([learnkabu.com](https://www.learnkabu.com/)) |
| **[LoanLens](https://github.com/HoldenRichard/LoanLens)** | Student loan analytics modeling real repayment and interest trajectories | Python, FastAPI, Kinde OAuth (2FA) | 1st in Fintech, 2nd Overall at UVM SWICS Hackathon (under 48 hrs) |
| **[TradeSim](https://github.com/HoldenRichard/TradeSim)** | Real-time 3D stock-trading simulator and market visualizer | C++, OpenGL, ImGui | Custom 3D rendering engine built prior to iOS transition |
| **[sms-enforcer-public](https://github.com/HoldenRichard/sms-enforcer-public)** | Event-sourced SMS lead-response SaaS for home-service businesses | Python, FastAPI, PostgreSQL, Redis | Outbox pattern, idempotent message dispatch, webhook lifecycle |

---

### Stack & Credentials

- **Languages:** Swift, Python, TypeScript, JavaScript, C++, SQL
- **Frameworks & Data:** SwiftUI, FastAPI, Flask, React, Next.js, PostgreSQL, Cloud Firestore, Redis, SQLite
- **Infra, Security & AI:** Docker, GitHub Actions, Firebase Cloud Functions, OAuth/JWT, App Attest, Claude Code, Gemini Computer Use
- **Certifications:** 6x Claude Academy Certifications (Anthropic)

---

[holdenrichard.com](https://www.holdenrichard.com/) · [learnkabu.com](https://www.learnkabu.com/) · [LinkedIn](https://linkedin.com/in/holden-richard) · [hgrichar@uvm.edu](mailto:hgrichar@uvm.edu)
