<h1 align="center">Hi, I'm Evgenii Korolev 👋</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=2F81F7&center=true&vCenter=true&width=650&lines=Backend+%2B+Automation+%2B+Integration+Engineer;Python+%7C+Java+%7C+TypeScript+%7C+SQL;Durable+job+runtimes+%C2%B7+API+integrations+%C2%B7+applied+LLM+workflows;Technical+Co-Founder+%40+GenVish" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://genvish.dev"><img src="https://img.shields.io/badge/Portfolio-genvish.dev-2F81F7?style=for-the-badge&logo=googlechrome&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/evgenii-korolev"><img src="https://img.shields.io/badge/LinkedIn-Evgenii%20Korolev-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
</p>

---

### 👨‍💻 About me

Backend, automation, and integration engineer with **6+ years of hands-on programming**, including **5+ years with Python** and **4+ years with Java**. I build durable backend systems, API integrations, browser automation, and applied AI/LLM workflows — from ambiguous requirements through architecture, implementation, testing, deployment, and iteration. Currently a **Technical Co-Founder at GenVish** and an **Automation Engineer at MIND**. Bachelor of Computer Science (Big Data), University of Wollongong.

### 🔭 Currently building

- **GenVish** — a durable async job runtime (Python `asyncio`, SQLite WAL, leases, crash recovery, idempotency, bounded retries), cross-language contracts between Python and TypeScript/Node, OAuth-based integrations (Gmail, Telegram, Brave Search), and LLM tool-calling workflows with Structured Outputs. Currently building an automated **website audit & lead-discovery pipeline**: crawls public business sites, runs accessibility (axe-core) and performance (CrUX) checks alongside SEO/technical audits, generates PDF audit reports and fixed-price proposals, and follows up through a Gmail OAuth outreach flow with a controlled send queue, bounce detection, and AI-assisted reply classification — all behind a governance-gated CI pipeline (short-lived branches, mandatory quality gate, automated squash-merge).
- **MIND** (real-time AI voice-translation video-conferencing platform for business) — as Automation Engineer, built an AI-driven lead-sourcing and enrichment project: researching and scraping target-company websites, using the Hunter API to identify contacts, and structuring leads for downstream processing, applying Apollo-style prospecting concepts and CRM-oriented lead handling.
- One measurable result so far: a proposal/document workflow at GenVish went from **~60–90 minutes of manual work to ~1 minute**.

### 🚀 Flagship projects

| Project | What it does | Stack |
|---|---|---|
| **GenVish Audit & Outreach Engine** | Automated website audit + lead-discovery pipeline: SEO/accessibility (axe-core)/performance (CrUX) audits → PDF report & fixed-price proposal generation → Gmail OAuth outreach with a controlled send queue, bounce detection, and AI reply classification, shipped through a governance-gated CI (autonomous short-lived-branch agents, mandatory quality gate, automated squash-merge) | Python, TypeScript, Playwright, axe-core, Gmail API, OpenAI API, Docker, GitHub Actions |
| **ReMo Matcher** | Matches ~100 messy free-form requests per batch against an ~800,000-row supplier catalogue — taxonomy routing → DuckDB retrieval → deterministic scoring gates → constrained Gemini shortlist, with regression/golden/adversarial test suites | Python, Streamlit, DuckDB, Gemini API, Railway, Cloudflare R2 |
| **AI Agent Travel Platform** | Multi-module flight search/booking/rescheduling agent with structured tool calling, idempotency, retries, and a simple circuit breaker (university project, CSCI318 — 80/100 Distinction) | Java 21, Spring Boot 3, Kafka, LangChain4j, Docker |
| **AU Census RAG Analyzer** | Hybrid FAISS + BM25 retrieval with deterministic numeric answering, LoRA/PEFT fine-tuning on Llama 3.2 1B | Streamlit, FAISS, BM25, Unsloth, TRL, MLflow |
| **TikTok/YouTube Content Automation** | Personal pipeline: ingest → transcription → clip selection → rendering → delivery, scaling output from ~5 to 40–50 clips/day | n8n, yt-dlp, Whisper, FFmpeg |
| **Python Gemini Tool-Calling Agent** | Single-agent tool loop with planner/executor and router modes, explicit tool registry, strict JSON routing | FastAPI, Pydantic, Gemini API, SQLite |

### 🛠️ Tech stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)

**Backend & web**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![VitePress](https://img.shields.io/badge/VitePress-5C73E7?style=flat-square)

**APIs, automation & AI**

![OAuth2](https://img.shields.io/badge/OAuth%202.0-3C3C3D?style=flat-square&logo=auth0&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI%20API-412991?style=flat-square&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini%20API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)
![axe-core](https://img.shields.io/badge/axe--core-8046F1?style=flat-square)
![APScheduler](https://img.shields.io/badge/APScheduler-2E7D32?style=flat-square)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)

**Data**

![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=flat-square&logo=googlebigquery&logoColor=white)

**Infra & tooling**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white)

### 🎓 Education & achievements

- **Bachelor of Computer Science (Big Data)**, University of Wollongong — awarded 24 July 2026 (UOW Dubai → UOW Australia)
- Selected results: Engineering Mathematics **99/100 HD**, Fundamental Programming with Python **96/100 HD**, Modern Artificial Intelligence **92/100 HD**, Web Technology **89/100 HD**
- 🏆 **2nd place, Sberbank Hackathon (2021)** — interactive map of perinatal centres across Russia, RANEPA university team

### 📫 Get in touch

[Portfolio](https://genvish.dev) · [LinkedIn](https://www.linkedin.com/in/evgenii-korolev)
