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

**Languages:** TypeScript · Python · Rust · Go
**Testing & evals:** Playwright · Cypress · promptfoo · `@kbn/evals`
**Platform:** Elasticsearch · Kibana · OpenTelemetry
**AI tooling:** MCP · Claude Code · Codex

## 💬 Let's talk

I'm happy to talk about evaluating LLM features, testing AI agents, MCP security, or how to make AI coding assistants useful to a whole team and not only to one enthusiastic developer.

📍 Near Madrid, Spain · [LinkedIn](https://www.linkedin.com/in/YOUR-HANDLE)

---

```python
while agent.is_nondeterministic():
    write_another_eval()
```
