# Hi, I'm Enrique 👋

**Senior QA Engineer at [Elastic](https://www.elastic.co), on the Kibana Security Solution team.**

I spend most of my time figuring out how to test software that doesn't give the same answer twice: AI agents, LLM-powered features, and the tooling developers use to build them.

Before Elastic I was a university professor teaching software quality, project management and software engineering, so I still can't resist turning a good bug into a lesson.

## 🔍 What I work on

- **AI evaluation:** contributing to [`@kbn/evals`](https://github.com/elastic/kibana), building golden-set evaluations and getting evals into CI for security product teams
- **Adversarial testing:** red-teaming AI agents with prompt injection, instruction override and other ways of making them misbehave
- **Developer enablement:** helping ~10 product teams get more out of AI coding assistants (Claude Code, Codex) through skills, plugins, evals and shared workflows
- **Test automation:** moving Kibana's Cypress suites to [Scout](https://github.com/elastic/kibana) (Playwright)

## 🛠️ Side projects

Most of these are about **MCP and AI agent security**, plus tools I build for my own workflow:

| Project | What it does | Status |
|---|---|---|
| **Vigil** | Runtime tripwire for Claude Code. Detects MCP tools and skills that change or turn malicious (rug pulls, prompt injection, credential-stealing scripts) | 🚧 In progress |
| **DevTrace** | MCP observability proxy that sends agent traces to Elasticsearch/Kibana using OTel GenAI conventions | 🚧 In progress |
| **mcpscan** | Layered security scanner for MCP servers, mapped to the OWASP LLM Top 10 | 🧪 Concept |
| **logsift** | Rust CLI that makes sense of noisy CI logs | ✅ |
| **chaos-reviewer** | Adversarial PR review agent written in Go (hackathon project) | ✅ |
| **ccrig** | CLI for A/B testing Claude Code configuration profiles | ✅ |

## 🧰 Tools I reach for

| Area | Tools |
|---|---|
| **Languages** | ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white) ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) |
| **Testing & evals** | ![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white) ![Cypress](https://img.shields.io/badge/Cypress-17202C?style=flat-square&logo=cypress&logoColor=white) ![promptfoo](https://img.shields.io/badge/promptfoo-FF6B35?style=flat-square) ![@kbn/evals](https://img.shields.io/badge/%40kbn%2Fevals-005571?style=flat-square&logo=elastic&logoColor=white) |
| **Platform** | ![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white) ![Kibana](https://img.shields.io/badge/Kibana-E8478B?style=flat-square&logo=kibana&logoColor=white) ![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-425CC7?style=flat-square&logo=opentelemetry&logoColor=white) |
| **AI tooling** | ![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square) ![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=claude&logoColor=white) ![Codex](https://img.shields.io/badge/Codex-412991?style=flat-square&logo=openai&logoColor=white) |

## 💬 Let's talk

I'm happy to talk about evaluating LLM features, testing AI agents, MCP security, or how to make AI coding assistants useful to a whole team and not only to one enthusiastic developer.

📍 Near Madrid, Spain · [LinkedIn](https://www.linkedin.com/in/YOUR-HANDLE)

---

```python
while agent.is_nondeterministic():
    write_another_eval()
```
