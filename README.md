# Hi, I'm Ahmed Houssou 👋
### Senior SDET & Test Infrastructure Engineer

Specializing in **autonomous test architectures, AI-augmented runtime resilience, and developer productivity tooling** across TypeScript, Playwright, Node.js, and CI/CD pipelines.

---

## 🛠️ Specialized Test Infrastructure & SDET Tools

A suite of open-source CI/CD test automation utilities engineered to eliminate flakiness, gate breaking changes, and automate root-cause triage across the software delivery lifecycle.

| Project | Domain | Architecture & Highlights | CI Status |
| :--- | :--- | :--- | :--- |
| [**`self-healing-playwright-agent`**](https://github.com/AhmedHoussou/self-healing-playwright-agent) | **AI & Runtime Resilience** | Intercepts Playwright locator timeouts, extracts interactive DOM candidate subtrees, and queries Gemini Flash Lite to synthesize valid selectors in <1.8s with local JSON caching. | [![CI](https://github.com/AhmedHoussou/self-healing-playwright-agent/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/AhmedHoussou/self-healing-playwright-agent/actions) |
| [**`action-test-failure-triage`**](https://github.com/AhmedHoussou/action-test-failure-triage) | **CI/CD Observability** | Published GitHub Action that parses raw runner logs, autonomously categorizes test failures (Bug, Flake, Selector Drift, Timeout, Infra), and posts deduplicated diagnostic summaries directly to PRs. | [![CI](https://github.com/AhmedHoussou/action-test-failure-triage/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/AhmedHoussou/action-test-failure-triage/actions) [![Marketplace](https://img.shields.io/badge/Marketplace-v1.0.0-blue?logo=github)](https://github.com/marketplace/actions/playwright-test-failure-triage) |
| [**`contract-guard`**](https://github.com/AhmedHoussou/contract-guard) | **Backend & Contracts** | Autonomous API contract & boundary fuzzing engine. Dereferences OpenAPI 3.0 `$ref` schemas, generates negative boundary mutations (type errors, boundary limits, missing required fields), and verifies JSON Schemas with compiled Ajv validators. | [![CI](https://github.com/AhmedHoussou/contract-guard/actions/workflows/ci.yml/badge.svg)](https://github.com/AhmedHoussou/contract-guard/actions) |
| [**`perf-guard`**](https://github.com/AhmedHoussou/perf-guard) | **Performance SLAs** | High-concurrency performance gating engine. Simulates parallel virtual-user loads, measures throughput and latency percentiles ($p50$, $p90$, $p95$, $p99$), and automatically fails CI builds if tail latency drifts beyond historical SLA baselines. | [![CI](https://github.com/AhmedHoussou/perf-guard/actions/workflows/ci.yml/badge.svg)](https://github.com/AhmedHoussou/perf-guard/actions) |
| [**`a11y-guard`**](https://github.com/AhmedHoussou/a11y-guard) | **Compliance & WCAG** | Automated accessibility compliance harness powered by Playwright and Axe-core. Audits active DOM trees against WCAG 2.0 / 2.1 / 2.2 Level A/AA standards and enforces strict quality gates on pull requests. | [![CI](https://github.com/AhmedHoussou/a11y-guard/actions/workflows/ci.yml/badge.svg)](https://github.com/AhmedHoussou/a11y-guard/actions) |
| [**`visual-guard`**](https://github.com/AhmedHoussou/visual-guard) | **Visual Regression** | Perceptual UI diffing engine integrating Playwright and Pixelmatch. Automates CSS selector masking on volatile UI elements (timestamps, dynamic tokens) to eliminate false positives while generating high-visibility diff artifacts for real layout breaks. | [![CI](https://github.com/AhmedHoussou/visual-guard/actions/workflows/ci.yml/badge.svg)](https://github.com/AhmedHoussou/visual-guard/actions) |

---

## 🧰 Technical Competencies

* **Languages & Core:** TypeScript, JavaScript (Node.js/ESM), Python, SQL, HTML5/CSS3.
* **Test Automation & Quality:** Playwright, Cypress, Selenium WebDriver, Contract Testing (OpenAPI/Ajv), Accessibility (Axe-core/WCAG), Visual Diffing (Pixelmatch), Performance & Load Simulation.
* **DevOps & Developer Experience:** GitHub Actions (Custom Marketplace Action Authoring), CI/CD Workflow Optimization, Docker, Git.
* **Architecture Paradigms:** Self-healing Test Runners, Automated Root-Cause Triage, Negative Mutation Fuzzing, Strict SLA Drift Gating.

---

## 📬 Connect

* **GitHub:** [AhmedHoussou](https://github.com/AhmedHoussou)
* **LinkedIn:** [Ahmed Houssou](https://www.linkedin.com/in/ahmed-houssou-a05394255/)
* **Email:** ahmedhoussou99@gmail.com
