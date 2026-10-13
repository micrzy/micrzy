# Hi, I'm Ying 👋

QA Engineer with 7+ years of experience testing healthcare SaaS and telecom platforms.
I build test automation with **Playwright and TypeScript**, and I use AI coding agents with **tests as the control layer**: generated code only counts when tests prove it works.

---

### 🧪 What I work on

- **E2E and API test automation:** Playwright, TypeScript, Page Object Model, custom fixtures, network mocking
- **CI quality gates:** GitHub Actions, Docker, tiered test suites
- **Performance testing:** k6 load and stress tests with thresholds and results analysis
- **AI-assisted testing:** Claude Code + Playwright MCP, turning Jira stories into Playwright tests

---

### ⭐ Featured projects

**[practicesoftwaretesting](https://github.com/micrzy/practicesoftwaretesting)** — Playwright + TypeScript framework for an e-commerce app
- UI and API tests with custom fixtures, API-seeded test data and Zod schema validation
- Tiered CI in GitHub Actions + Docker: `@sanity` on every PR, `@smoke` on merge, `@regression` on demand
- Runs against a self-hosted copy of the app, reseeded on every run
- k6 load and stress tests with a written results analysis

**[job-application-tracker](https://github.com/micrzy/job-application-tracker)** — single-file HTML dashboard for tracking job applications: status, interviews, response times

🚧 **Building:** an AI agent (Claude Code + Playwright MCP + Jira) that reads a Jira story, writes and runs a Playwright test, fixes its own test code when it fails, and moves the story to Done. Rules keep it honest: every acceptance criterion becomes an assertion, and assertions are never weakened to get a green run.

---

### 🛠️ Tools

Playwright · TypeScript · k6 · Postman · SQL · GitHub Actions · Docker · Jira · Claude Code · MCP · Burp Suite
