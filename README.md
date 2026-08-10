# Hi, I'm Evgenii (Eugene) Menshikov 👋

### AI Automation Engineer — I build AI systems and **test them to hold up in production.**

I work **spec-first** — requirements → design → build → test → deploy — so what I ship survives
contact with real users. That QA discipline is the part most AI work skips, and it's my edge.
Everything below is running, tested, and readable.

🌐 **[artjeck.com](https://www.artjeck.com)** · ✉️ **[hello@artjeck.com](mailto:hello@artjeck.com)** · 💼 **[LinkedIn](https://www.linkedin.com/in/evgenii-menshikov-751733132)**

---

### 🚀 Flagship work

| Project | What it is |
| --- | --- |
| **[ifta-agent](https://github.com/ArtJack/ifta-agent)** | Production IFTA fuel-tax filing pipeline for interstate carriers. Deterministic math plus an LLM review agent over 18 grounded tools. **429 tests**, backtested to reproduce a real state filing **to the penny**, ~$0.10/filing. *Live, serving a paying carrier.* |
| **[sales-agent-showcase](https://github.com/ArtJack/sales-agent-showcase)** | Clean-room showcase of a multi-marketplace commerce agent running a live resale business. **Irreversible actions are human-gated structurally** — the reprice call asserts its own execution grant, so there's no code path to the write without an approved approval. **30 tests**, CI, runnable on synthetic data. |
| **[second-brain](https://github.com/ArtJack/second-brain)** | Local-first **RAG** assistant: answers only from your own notes, docs and code, every claim cited, graded by an eval harness. Exposed over **MCP**. |
| **[lab-control-mcp](https://github.com/ArtJack/lab-control-mcp)** | **MCP** server operating a self-hosted AI lab, with a safety-gated remote shell — allowlist, no shell metacharacters, hard timeouts. |
| **[email-agent](https://github.com/ArtJack/email-agent)** | Self-hosted inbox triage on **local Ollama — $0 LLM cost**. IMAP → classify → daily Telegram digest, scheduled via launchd, SQLite dedupe so reruns never double-notify. |
| **[liora-studio](https://github.com/ArtJack/liora-studio)** | Full-stack e-commerce storefront and admin CMS with **TOTP 2FA**. Next.js App Router + Prisma. |

Also here: **[bol-extractor](https://github.com/ArtJack/bol-extractor)** (Bill of Lading PDF → structured data) and
**[dm-express-site](https://github.com/ArtJack/dm-express-site)** (production client site; boundary-value analysis
caught a real off-by-one at the 1 MB rollover).

### 🧰 What I work with

**AI** — agents · RAG · MCP servers · evals · agent guardrails · prompt engineering · Anthropic SDK · LiteLLM · Ollama · Qdrant
**Build** — Python · TypeScript · FastAPI · Next.js · React · Postgres / SQLite · Alembic
**Quality** — spec-driven development · regression & edge-case testing · equivalence partitioning · boundary value analysis · decision tables

### 🏠 Self-hosted AI lab

An always-on lab (Mac mini + Alienware over Tailscale) running **free local models** behind one
gateway, with two MCP servers I built and a vector store for retrieval. Free-by-default inference —
I only pay for a frontier model when the task is worth it.

### 🧭 Domain edge

I've spent years building and supporting compliance systems for interstate carriers, so the problems
I solve in that space — IFTA filing, Bill of Lading parsing, fuel-tax reconciliation — are ones I
understand end to end. Most engineers never see this domain; most people in it can't build software
for it. That overlap is where my best work comes from.

---

<sub>Open to AI engineering, AI automation, and QA roles — remote, Sacramento, or the Bay Area.</sub>
