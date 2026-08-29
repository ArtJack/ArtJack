# Evgenii (Eugene) Menshikov

### AI Automation Engineer — I build AI systems and **test them end to end.

I work **spec-first** — requirements → design → build → test → deploy — so what I ship survives
contact with real users. That QA discipline is the part most AI work skips, and it's my edge.
Everything below is running, tested, and readable.

🌐 **[artjeck.com](https://www.artjeck.com)** · ✉️ **[hello@artjeck.com](mailto:hello@artjeck.com)** · 💼 **[LinkedIn](https://www.linkedin.com/in/evgenii-menshikov)**

---

### 📌 At a glance

- **Production LLM pipeline, live:** [ifta-agent](https://github.com/ArtJack/ifta-agent) files real quarterly IFTA fuel-tax returns for an interstate carrier — **555 automated tests**, backtested against a real state filing **to the penny**, ~$0.10 model cost per reviewed return. Its LLM review agent (**17 grounded tools**) caught filing errors the manual process had been making for years.
- **Published AI QA agent:** [verdict](https://github.com/ArtJack/verdict) — baseline → delta runs, flaky quarantine, evidence-cited release verdicts. Validated by its own seeded-defect eval: **8/8 planted defects found** on the first published run.
- **Human-in-the-loop by architecture:** an 8-marketplace commerce engine where irreversible actions are **structurally gated** behind human approval — no approved grant, no code path to the write.
- **Stack:** Python · TypeScript · FastAPI · Next.js · Anthropic SDK · MCP (built 2 servers from scratch) · RAG/Qdrant · Ollama/LiteLLM self-hosted lab.
- **Open to:** AI engineering · AI automation · QA — remote (US), Sacramento, or SF Bay Area. Also available for **freelance builds** via [ArtJack Technology](https://www.artjeck.com).

### 🚀 Flagship work

| Project | What it is |
| --- | --- |
| **[ifta-agent](https://github.com/ArtJack/ifta-agent)** | Production IFTA fuel-tax filing pipeline for interstate carriers. Deterministic math computes every number on the form; an LLM review agent over **17 grounded tools** audits each return against the rulebook and the client's filing history — it caught errors humans had been making for years. **555 tests**, penny-accurate regression, ~$0.10/filing. *Live, filing every quarter for a paying carrier.* |
| **[verdict](https://github.com/ArtJack/verdict)** | A skeptical **AI QA agent with memory**: establishes a baseline, then reports only NEW/REGRESSED findings, quarantines flaky tests with expiry, and issues evidence-cited release verdicts. Ships its own **seeded-defect eval (8/8)**. |
| **[sales-agent-showcase](https://github.com/ArtJack/sales-agent-showcase)** | Clean-room showcase of a multi-marketplace commerce agent running a live resale business. **Irreversible actions are human-gated structurally** — the reprice call asserts its own execution grant, so there is no code path to the write without an approved approval. 30 tests, CI, runnable on synthetic data. |
| **[second-brain](https://github.com/ArtJack/second-brain)** | Local-first **RAG** assistant: answers only from your own notes, docs and code, every claim **cited to source**, graded by an eval harness with citation grading. Exposed over **MCP**. |
| **[lab-control-mcp](https://github.com/ArtJack/lab-control-mcp)** | **MCP** server operating a self-hosted AI lab, with a safety-gated remote shell — allowlist, no shell metacharacters, hard timeouts. |
| **[email-agent](https://github.com/ArtJack/email-agent)** | Self-hosted inbox triage on **local Ollama — $0 LLM cost**. IMAP → classify → daily Telegram digest, scheduled via launchd, SQLite dedupe so reruns never double-notify. |

Also here: **[liora-studio](https://github.com/ArtJack/liora-studio)** (full-stack e-commerce + admin CMS with TOTP 2FA),
**[greek-scythian-society-website](https://github.com/ArtJack/greek-scythian-society-website)** (client site — Docker/Caddy WordPress, one idempotent script from bare VM to live),
and **[bol-extractor](https://github.com/ArtJack/bol-extractor)** (Bill of Lading PDF → structured data).

### 🧰 What I work with

**AI** — agents · RAG · MCP servers · evals · agent guardrails · human-in-the-loop design · prompt engineering · Anthropic SDK · LiteLLM · Ollama · Qdrant · LangGraph
**Build** — Python · TypeScript · FastAPI · Next.js · React · Postgres / SQLite · Docker · Playwright
**Quality** — spec-driven development · formal test design (equivalence partitioning · boundary value analysis · decision tables) · testing non-deterministic systems · seeded-defect evals

A boundary-value pass on a client web app once caught a real off-by-one exactly at the 1 MB rollover
(`"1024 KB"` instead of `"1.0 MB"`) — the kind of bug nobody files a ticket for and every user notices.

### 🏠 Self-hosted AI lab

An always-on lab (Mac mini + Alienware over Tailscale) running **free local models** behind one
gateway, with two MCP servers I built and a vector store for retrieval. Private by default —
client data stays inside the building; I reach for a frontier model only when the task earns it.

### 🧭 Domain edge

Years of building and supporting **compliance and back-office systems for small logistics businesses** —
IFTA filing, Bill of Lading parsing, fuel-tax reconciliation, DOT/ELD data. Most engineers never see
this domain; most people in it can't build software for it. That overlap is where my best work comes from.

### 🤝 Work with me

**Hiring?** I'm open to AI engineering, AI automation, and QA roles — remote (US), Sacramento, or SF Bay Area.
**Need something built?** [ArtJack Technology](https://www.artjeck.com) ships websites, e-commerce, AI automation,
and compliance pipelines for small businesses — fixed scope, tested, documented.

<sub>✉️ hello@artjeck.com · 🌐 [artjeck.com](https://www.artjeck.com) · 💼 [linkedin.com/in/evgenii-menshikov](https://www.linkedin.com/in/evgenii-menshikov)</sub>
