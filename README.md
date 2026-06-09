<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=28&duration=2800&pause=900&color=58A6FF&center=true&vCenter=true&width=600&lines=manish%40botta%3A~%24+whoami;Software+%2F+AI+Engineer;GenAI+Developer+%C2%B7+Forward+Deployed" alt="manish@botta:~$ whoami — Software / AI Engineer" />

<br/>

<a href="https://manishbotta.me"><img src="https://img.shields.io/badge/portfolio-manishbotta.me-58A6FF?style=for-the-badge&logo=googlechrome&logoColor=0d1117&labelColor=0d1117" alt="Portfolio"/></a>
<a href="https://linkedin.com/in/manish-reddyb"><img src="https://img.shields.io/badge/linkedin-manish--reddyb-58A6FF?style=for-the-badge&logo=linkedin&logoColor=0d1117&labelColor=0d1117" alt="LinkedIn"/></a>
<a href="https://simcricketx.app"><img src="https://img.shields.io/badge/live-simcricketx.app-58A6FF?style=for-the-badge&logo=googlechrome&logoColor=0d1117&labelColor=0d1117" alt="SimCricketX"/></a>

</div>

```console
manish@botta:~$ neofetch

        ███╗   ███╗ ██████╗        user        :: manish@botta
        ████╗ ████║ ██╔══██╗       role        :: Software / AI Engineer · Forward Deployed
        ██╔████╔██║ ██████╔╝       location    :: Los Angeles, CA
        ██║╚██╔╝██║ ██╔══██╗       uptime      :: 3+ years in production
        ██║ ╚═╝ ██║ ██████╔╝       shell       :: Python · TypeScript · Node.js · Java
        ╚═╝     ╚═╝ ╚═════╝        kernel      :: LangGraph · RAG · QLoRA · RLHF/RLAIF
        ░▒▓ ai.engineer ▓▒░        packages    :: FastAPI · Redis · Kafka · PostgreSQL · Docker
                                   hosts       :: AWS · Azure · OCI
```

## `❯ cat about.txt`

I build and ship **production GenAI systems end to end** — agentic LangGraph workflows, RAG pipelines, and LLM fine-tuning, plus the FastAPI / Redis / Docker infrastructure underneath them. I care about the parts most demos skip: **guardrails, tracing, and failure handling** — and I've taken several systems from an empty repo to a live URL solo.

Forward-deployed at heart: shipped GenAI systems to **24+ enterprise clients** (IHCL, Dr. Reddy's, Bajaj Finserv, Spotify), owning on-site integration, dual-sided InfoSec approvals, demos, and onboarding.

```python
class Manish:
    uptime    = "3+ years in production"
    shipped   = ["100M+ daily conversations", "24+ enterprise clients", "99.9% uptime SLA"]
    open_to   = ["Software Engineer", "AI Engineer", "GenAI Developer", "Forward Deployed Engineer"]
```

## `❯ git log --career --oneline`

```console
a4f2026 (HEAD -> main)      TradeLiv   · Founding Software Engineer        Apr 2026 → now
b7e2025 (genai/agents)      Microsoft  · Software Engineer                 Aug 2025 → Mar 2026
c3d2021 (forward-deployed)  Yellow.AI  · Software Engineer (FDE / Studio)  Sep 2021 → Jul 2023
d1c2021 (init)              Cognizant  · Program Trainee Analyst           Mar 2021 → Aug 2021
```

- **TradeLiv** — sole engineer, zero → production: 40+ REST endpoints, PostgreSQL, Stripe, real-time SSE portals, RBAC — live at [tradeliv.design](https://tradeliv.design). One Claude + Browserless Chrome extractor replaced every brittle per-site scraper.
- **Microsoft** — LLM-powered autonomous agents (FastAPI, LangChain, tool-use, memory, planning); real-time RLHF/RLAIF ingestion loops (**+60%** data freshness); containerized AI microservices with **−40%** integration defects.
- **Yellow.AI** — GenAI chatbots for 24+ enterprise clients; LoRA/QLoRA fine-tuning lifted accuracy **60%** and CSAT **35%** across **100M+ daily conversations**; RLHF reward checkpoints cut harmful responses **28%**; Node.js/Kafka backbone at **99.9% uptime**.
- **Cognizant** — legacy Java monolith → Spring Boot microservices, **+30%** velocity, **−40%** query time, 80%+ coverage.

## `❯ ls -la ~/projects --sort=impact`

| project | what it does | stack |
|---|---|---|
| **[role-collector](https://github.com/Manishrdy/role-collector)** | 13-node LangGraph job-sourcing agent — local Ollama (qwen3:8b), Langfuse tracing with PII redaction, hard-coded URL-allowlist guardrails, beat Google's CDP-layer bot detection via nodriver. 55 passing tests. | `LangGraph` `Ollama` `Langfuse` `Pydantic` |
| **[SimCricketX](https://simcricketx.app)** | Real-time probabilistic cricket simulation — 256+ users, 444+ matches in production; ~21K lines, 126 endpoints, 7-layer momentum engine; 120 deliveries resolved in <5s. [repo ↗](https://github.com/Manishrdy/SimCricketX) | `Python` `Flask` `WebSockets` `OCI` |
| **[async-audio-pipeline](https://github.com/Manishrdy/async-audio-pipeline)** | Queue-based async meeting intelligence — Splitter → Transcriber → Summarizer workers over Redis; 1-hour meetings in 7–11 min (vs 45–75 baseline); workers scale with zero API changes. | `FastAPI` `Redis` `Whisper` `Gemini` |
| **[AI-Driven-Resume-Builder](https://github.com/Manishrdy/AI-Driven-Resume-Builder)** | RAG + alignment — FAISS hybrid retrieval + cross-encoder re-ranking (**+45%** match scores); QLoRA at 4-bit (**−60%** GPU memory); Constitutional AI self-critique loops. | `FAISS` `QLoRA` `RLHF` `HuggingFace` |
| **[applyd](https://github.com/Manishrdy/applyd)** | Multi-service job aggregation — Argon2id auth, three-signal expired-job state machine across 10+ ATS providers, per-ATS circuit breakers that fail closed, tamper-evident audit log. | `FastAPI` `SQLite` `FTS5` |

## `❯ tree ~/skills --depth=1`

```text
skills/
├── languages          Python · TypeScript · Node.js · Java · SQL
├── ai_ml              LangGraph · LangChain · RAG · FAISS · QLoRA/LoRA · RLHF/RLAIF · Langfuse · BERT
├── models_tools       Claude · OpenAI · Whisper · Gemini · Ollama · HuggingFace
├── backend_data       FastAPI · Flask · Express.js · Spring Boot · PostgreSQL · MongoDB · Redis · Kafka
├── cloud_devops       AWS · Azure · OCI · Docker · GitHub Actions · Nginx · REST · JWT · OAuth 2.0
└── customer_delivery  Client Onboarding · On-Site Integration · InfoSec Reviews · Stakeholder Demos
```

## `❯ gh stats --user manishrdy`

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=manishrdy&show_icons=true&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=c9d1d9&count_private=true" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=manishrdy&layout=compact&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&langs_count=6" alt="Top languages" />
  <br/><br/>
  <img src="https://streak-stats.demolab.com?user=manishrdy&hide_border=true&background=0d1117&ring=58a6ff&fire=ffc66d&currStreakLabel=58a6ff&sideLabels=c9d1d9&currStreakNum=f0f6fc&sideNums=f0f6fc&dates=8b949e" alt="GitHub streak" />
</div>

## `❯ ping manish`

```console
manish@botta:~$ ping manish
64 bytes from mabotta12@gmail.com: response_time < 24h
64 bytes from linkedin.com/in/manish-reddyb: status=open_to_work
64 bytes from manishbotta.me: portfolio=live

--- open to: SWE · AI Engineer · GenAI Developer · Forward Deployed Engineer ---
manish@botta:~$ exit 0
```

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=manishrdy&style=flat-square&color=58a6ff&label=visitors" alt="Profile views"/>
</div>
