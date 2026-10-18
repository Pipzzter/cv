# Filip Jordanoski

**AI Full-Stack Engineer** · AI agents · Multi-agent orchestration · RAG & search · FastAPI + Vue

[pipojordanoski@gmail.com](mailto:pipojordanoski@gmail.com) · [+389 70 207 736](tel:+38970207736) · Skopje, North Macedonia (remote)

[linkedin.com/in/pipojordanoski](https://www.linkedin.com/in/pipojordanoski) · [github.com/Pipzzter](https://github.com/Pipzzter) · [upwork.com/freelancers/pipo](https://www.upwork.com/freelancers/pipo)

---

## Professional summary

AI full-stack engineer who builds production LLM systems: multi-agent orchestration with LangGraph, AI agents with tool
calling, RAG and hybrid search, and Claude skill pipelines, on FastAPI, PostgreSQL and Vue. Freelancing on Upwork since
February 2026 with 5-star client reviews, after AI engineering roles at YipYap and Cognirum. Builds for reliability
(retries and model fallback, checkpointed runs, schema-validated output, human review where errors compound) and owns
delivery from architecture to deployment.

## Technical skills

- **Languages:** Python, TypeScript, JavaScript, SQL, PHP
- **AI & LLMs:** OpenAI, Anthropic Claude, Gemini, Grok, DeepSeek · LangGraph, LangChain · RAG, hybrid search (BM25 +
  vectors), pgvector, sentence-transformers · tool calling, structured output (Pydantic) · Claude Skills · prompt
  engineering
- **Backend:** FastAPI, async SQLAlchemy, Alembic, Pydantic, Socket.IO, Node.js, Deno, Django, REST APIs
- **Frontend:** Vue 3, TypeScript, Vite, Pinia, Tailwind CSS, React, Nuxt.js
- **Data:** PostgreSQL (full-text search, pgvector), SQLite, Prisma
- **DevOps:** Docker, GitHub Actions CI/CD, Caddy, Nginx, DigitalOcean, Render, Cloudflare Tunnels, pytest, Ruff,
  pre-commit
- **AI development:** Claude Code (main coding tool, every project), Codex (animations, logo and brand design)
- **Platforms:** Base44, GitHub Copilot, Shopify GraphQL, Make.com, n8n, Stripe, Framer, Selenium, Scrapy

## Work experience

### Freelance AI Full-Stack Engineer · [Upwork](https://www.upwork.com/freelancers/pipo)

**February 2026 – Present** · Remote

- **SornAI, SEO & AI-visibility strategy agent** (Sorn, SEO agency · Jun – Sep 2026): replaced the agency's brittle
  strategy prompt with a Claude skill chain (an orchestrator and 12 stage skills) that turns Search Console, Ahrefs,
  GA4 and crawl exports into a client-ready strategy (.docx) and an E-E-A-T audit, with two human-review checkpoints,
  deterministic figures and a 29-rule guardrail contract against invented data.
- **OTTO, AI buyer's agent** (Think Auto, Australian car-buying platform · Jun 2026 – Present): AI agent on Base44 that
  routes each shopper's request to the right tool (vehicle search, valuation, market pricing, lead capture) with
  fallbacks, typo tolerance and banded prices; ongoing work on the platform's flows, Deno backend functions and admin
  CRM.
- **Hybrid search & research overviews** (Faculti, academic video platform · Feb 2026 ·
  [walkthrough](https://www.loom.com/share/51768c1b805249269696f13fde705265)): hybrid search in the client's PostgreSQL
  (full-text + pgvector with HNSW) with a category-first stage, intent detection and weighted ranking across 6,000+
  expert videos, 500k+ clips and papers, plus an LLM overview grounded in the results.
- **Multi-agent e-commerce orchestrator** (EverCart AI · Mar 2026): orchestrator foundation with Postgres checkpointing
  and a Grok → Claude fallback, driven by a JSON workflow; since published as
  [StoreForge AI](https://github.com/Pipzzter/storeforge).
- **Landing-page automation** (Growevity, e-commerce · Feb – Mar 2026): copy-injection agent that fills HTML
  landing-page templates from raw copy, with dynamic sections and generated images; rebuilt the client's five templates.

### AI Full-Stack Engineer · YipYap

**October 2025 – February 2026** · Remote · Embeddable AI agent SaaS platform

- Built the platform where businesses turn their own files and web pages into AI agents and embed them on any site with
  one `<script>` tag (Intercom-style).
- Agent builder and ingestion: system prompts, uploads and URLs into per-agent knowledge bases; document processing for
  PDF, DOCX, CSV, TXT, MD and JPG; web-page scraping and indexing.
- Provider-agnostic Model Factory with tool calling, hybrid RAG (BM25 + vectors), token-by-token Socket.IO streaming,
  and a multi-tenant FastAPI + PostgreSQL backend with per-tenant token tracking.

Stack: FastAPI · Vue 3 · PostgreSQL · Docker · Socket.IO · LangChain

### Cognirum · Skopje, North Macedonia

AI support copilot

**AI Full-Stack Engineer** · February 2025 – September 2025

- Built the internal AI Support Copilot used by the customer support team, end to end on FastAPI, PostgreSQL,
  LangChain and Vue.js.
- Agentic tool calling that runs SQL against operational databases (order status, shipment tracking, user lookups);
  hybrid RAG (BM25 + dense vectors) over policies and SOPs; a dashboard showing the agent's reasoning steps and tool
  calls.

**AI R&D Intern** · August 2024 – January 2025

- RAG benchmarking system (chunking strategies, retrieval algorithms, generation quality) and the company's first hybrid
  search prototype (BM25 + dense embeddings), with tuned chunk size, overlap, top-k and similarity thresholds.

### Involve · Skopje, North Macedonia

**Junior Web Developer** · March 2024 – May 2024

- Admin panel improvements across frontend and backend in JavaScript and PHP.

**Web Scraping Engineer** · July 2023 – September 2023

- Scraping pipelines with Selenium and Scrapy, including anti-bot handling, delivering clean, structured data.

## Projects

### [StoreForge AI](https://github.com/Pipzzter/storeforge)

[github.com/Pipzzter/storeforge](https://github.com/Pipzzter/storeforge) · LangGraph · FastAPI · PostgreSQL · Claude · Grok

Multi-agent system: a founder's five-question intake becomes a 7-day launch plan, a sourced product line with margins and
the Shopify GraphQL code for the store; Claude / Grok routing with retries and fallback, Postgres checkpoints so runs
resume, 52 tests that run without API keys.

### [PaperMind](https://github.com/Pipzzter/papermind)

[github.com/Pipzzter/papermind](https://github.com/Pipzzter/papermind) · FastAPI · Vue 3 · PostgreSQL + pgvector · Gemini · OpenAI

RAG study platform: PDFs and notes become shared Knowledge Spaces, answers cite the exact source page, retrieval is
hybrid and permission-aware, and the same material generates study guides, graded quizzes and spaced-repetition
flashcards.

### [Advertly](https://github.com/Pipzzter/advertly)

[github.com/Pipzzter/advertly](https://github.com/Pipzzter/advertly) · FastAPI · Gemini 2.5 Flash + Image · Vue 3 · Docker

Raw advertorial copy in, a publishable landing page out: Gemini extracts typed sections, deterministic code fills the
HTML template, and Gemini image generation fills every image slot.

### [Sostojka](https://github.com/Pipzzter/sostojka)

[github.com/Pipzzter/sostojka](https://github.com/Pipzzter/sostojka) · Python · FastAPI · OpenAI tool calling

Agentic entity linking of Macedonian recipe ingredients to USDA FoodData Central: a five-stage, tool-using pipeline that
shows every reasoning step and confidence (implements the method from Darko Gjorgjievski's thesis).

### [Nedelko](https://github.com/Pipzzter/nedelko)

[github.com/Pipzzter/nedelko](https://github.com/Pipzzter/nedelko) · Node.js · Preact · SQLite · OpenAI

Team of three, 3-day hackathon: an AI weekly planner for kindergarten teachers with bilingual plans under strict schema
validation and live air-quality and weather data that move lessons indoors; 249 tests, SonarQube quality gate.

### [FastAPI + Vue Starter](https://github.com/Pipzzter/fastapi-vue-starter)

[github.com/Pipzzter/fastapi-vue-starter](https://github.com/Pipzzter/fastapi-vue-starter) · FastAPI · Vue 3 · Docker · GitHub Actions

Production starter: JWT auth with Argon2, async SQLAlchemy with Alembic migrations, rate limiting, health probes,
multi-stage Docker builds, Ruff, pytest and CI from the first commit.

### [Brza Faktura](https://brzafaktura.mk)

[brzafaktura.mk](https://brzafaktura.mk) · FastAPI · Vue 3 · PostgreSQL · Docker · Caddy

Live e-invoicing SaaS for Macedonian businesses, built solo (private repo): multi-tenant organizations with team roles,
email and Google sign-in, invoices, and company verification plus official codelists through the tax authority's (UJP)
API, with e-invoice submission in progress; English, Macedonian and Albanian UI.

## Education

**Faculty of Computer Science and Engineering (FINKI)**, Ss. Cyril and Methodius University in Skopje\
B.Sc. in Computer Science, 2023 – 2027 (expected)

## Certifications

- [Claude Code in Action](https://verify.skilljar.com/c/8cygx6tojpk7) · Anthropic
- [Career Essentials in Generative AI](https://www.linkedin.com/learning/certificates/145c0e6c3ef05f256278ca208807534b6517db37bdbc8540961b914b51629c04) · Microsoft & LinkedIn

## Languages

- **English:** Fluent
- **Macedonian:** Native
