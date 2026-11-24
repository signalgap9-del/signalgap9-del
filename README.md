# Yunseop Im

Full-stack and backend engineer building production **AI agents**, **RAG pipelines**, and **on-prem LLM serving** systems.

Right now I build workflow backends and the AI agent layer for a manufacturing PLM platform: revision-safe engineering data models, hybrid retrieval and knowledge-graph grounding over 20,000+ technical documents, and LLM inference on customer GPUs (`SGLang`) where engineering data cannot leave the site.

Outside day-to-day product work, I built and run a real-time multimodal AI agent SaaS on Cloudflare Workers and Durable Objects (MCP tool execution, per-tenant RAG, and idempotent multi-provider billing), contributed bug fixes to [NVIDIA/NVSentinel](https://github.com/NVIDIA/NVSentinel/pulls?q=is%3Apr+author%3Asignalgap9-del), and am completing an M.S. in Computer Science (AI) at Georgia Tech. Most of my public repos and [writing](https://signalgap9-del.github.io/writing/) focus on what makes AI agents and backends dependable in production: tenant isolation, PostgreSQL concurrency, deterministic agent guardrails, and evaluation harnesses.

[Portfolio](https://signalgap9-del.github.io) · [Writing](https://signalgap9-del.github.io/writing/) · [Resume](https://signalgap9-del.github.io/resume.html) · [LinkedIn](https://www.linkedin.com/in/yunseop-i-207a7215a/) · [signalgap9@gmail.com](mailto:signalgap9@gmail.com)

---

## Selected work

- **[Independent AI SaaS (stealth)](https://signalgap9-del.github.io/projects/ai-copilot-saas.html)**: real-time multimodal AI agent SaaS, built and operated in production with a split-agent loop (video model + tool-driving agent session), Cloudflare Workers/Durable Objects edge runtime, multi-provider LLM routing via AI Gateway, per-tenant RAG, OpenMeter + BigQuery usage pipeline, and public MCP server.
- **[devin-harness](https://github.com/signalgap9-del/devin-harness)**: open-source harness for running autonomous AI agents safely (MIT) with hook lifecycle, deterministic `<50ms` exec/file guards, typed review gates, action ledger, and a 30-doc engineering corpus.
- **[production-starter](https://github.com/signalgap9-del/production-starter)**: supply-chain hardened GitHub service template (MIT) with SHA-pinned Actions, SLSA build provenance, OpenSSF Scorecard, CodeQL, TruffleHog secret scanning, Playwright smoke E2E, UK GDS ops standards, and ADRs.
- **[graphrag-lab](https://github.com/signalgap9-del/graphrag-lab)**: GraphRAG pipeline in pure Python stdlib combining BM25 + knowledge-graph expansion over SQLite, 8 tests, zero dependencies.
- **[FreightScaler](https://github.com/signalgap9-del/peachtree-dispatch)**: multi-tenant freight risk intelligence SaaS with React/TypeScript frontend, AWS serverless backend (Lambda, DynamoDB, Kafka/CDC), OR-Tools route optimization, and 24 ADRs.

## Writing

- [PostgreSQL internals for multi-tenant backends: MVCC, SSI (40001), SKIP LOCKED, EXPLAIN BUFFERS & RLS](https://signalgap9-del.github.io/writing/postgres-internals.html)
- [Production AI agent architecture: open-source cores, pass^k evals (Inspect AI) & failure modes](https://signalgap9-del.github.io/writing/agent-architecture-evals.html)
- [Architecting a real-time multimodal agent SaaS: Durable Objects, AI Gateway, micro-USD ledgers & OpenMeter](https://signalgap9-del.github.io/writing/multimodal-agent-architecture.html)
- [GraphRAG for e-commerce: why product catalogs break naive RAG](https://signalgap9-del.github.io/writing/graphrag-ecommerce.html)
- [On-prem AI is a services business (opinion)](https://signalgap9-del.github.io/writing/onprem-ai-services.html)
- [Running LLM inference on customer GPUs: on-prem serving field notes](https://signalgap9-del.github.io/writing/onprem-llm.html)
- [Running autonomous AI agents safely: devin-harness teardown](https://signalgap9-del.github.io/writing/agents.html)
- [Building a real-time freight risk intelligence SaaS](https://signalgap9-del.github.io/writing/freightscaler.html)
- [Per-tenant RAG isolation in multi-tenant AI SaaS](https://signalgap9-del.github.io/writing/tenant-rag.html)
- [The production AI open-source stack worth adopting](https://signalgap9-del.github.io/writing/oss-stack.html)

## Stack

Python · TypeScript · Java · React · FastAPI · Node.js · Spring Boot · PostgreSQL · Redis · Kafka · gRPC · Qdrant · Docker · Kubernetes · AWS · GCP · Cloudflare · SGLang · vLLM · MCP · Langfuse

## Availability & Links

- **Relocation & work authorization:** Open to relocation across the **Netherlands, EU, UK, and US**. Dutch **Zoekjaar** (Orientation Year) visa holder (no sponsorship required in the Netherlands, HSM-eligible); visa sponsorship welcome elsewhere.
- **Site:** [signalgap9-del.github.io](https://signalgap9-del.github.io) · **Resume:** [resume.html](https://signalgap9-del.github.io/resume.html) · **LinkedIn:** [yunseop-i-207a7215a](https://www.linkedin.com/in/yunseop-i-207a7215a/) · **Email:** signalgap9@gmail.com
