# Yunseop Im

**Full-Stack Software Engineer — AI Products**
Currently building the AI layer of a PLM platform at **AinX** (Suwon, South Korea) — RAG/GraphRAG over 20,000+ engineering documents, LLM serving on customer GPUs. Previously shipped a real-time multimodal AI SaaS solo. M.S. Computer Science, Georgia Tech.

*Open to work — relocating to the Netherlands (Dutch Orientation Year visa, expected early 2027). Remote OK.*

---

## What I do

I build production AI systems end to end — React/TypeScript clients, FastAPI/Node/Spring Boot services, and the retrieval + inference layers in between. The through-line: **systems whose outputs can be checked** — cited answers, approval-gated changes, quantified risk, verified benchmarks.

## Currently — AinX · TechMentor (AI-native PLM)

- Backend modules for a PLM platform: drawings, documents, BOMs, MCAD/ECAD data on a revision model that keeps parts/CAD/drawings in sync and locks released data
- Engineering change workflow (ECR→ECO→ECN): approval routing, BOM impact analysis, effectivity rules, ERP/MES release services with audit trail
- **TechMentor AI layer**: hybrid sparse+dense retrieval (Qdrant), reciprocal rank fusion, cross-encoder reranking, knowledge-graph grounding (PostgreSQL + Apache AGE) — 20,000+ documents with citations to exact part + revision
- **On-prem LLM serving**: SGLang + Gemma on customer GPUs — continuous batching, KV-cache tuning, guided decoding for cited output; engineering data never leaves the site

## Independent products

| Project | What it is |
|---|---|
| **[LivePair AI](https://livepairai.com)** — livepairai.com | Real-time multimodal assistant on Cloudflare Workers — watches the screen + hears the call, surfaces help live. Split-agent loop (Gemini video windows + OpenAI Agents), per-tenant RAG isolation, 12-tool MCP server, OpenAPI 3.1, prepaid billing + x402 payments. Cut agent API cost $12 → $8/session-hour |
| **[FreightScaler / AtmosPath](https://github.com/signalgap9-del/peachtree-dispatch)** | Freight risk-intelligence SaaS — React/TS + AWS serverless (Lambda, DynamoDB, CloudFront), OR-Tools VRP, NWS/NOAA hazard data, multi-tenant quotas + idempotency, 24 ADRs, live demo deployed. [Architecture writeup](/writing/freightscaler.html) |
| **[devin-harness](https://github.com/signalgap9-del/devin-harness)** | Open-source operating system for agentic repos — lifecycle hooks, deterministic exec/file guards, action ledger, typed LLM review gates, dispatch contract, skills library. MIT |

## Background

- **Georgia Tech** — M.S. Computer Science, AI specialization (GPA 3.22). ML, Software Architecture, Distributed Systems coursework
- **E-commerce AI** (contract) — LangChain/OpenAI chatbot for 5,000 members; verification layer cut unsupported claims 25% → 10%
- **Namu ICT** — Samsung 5G cloud network platform; diagnosed peak-hour dashboard slowdowns for Verizon/Telus/Orange
- **Open source** — 2 merged PRs to [NVIDIA/NVSentinel](https://github.com/NVIDIA/NVSentinel) (GPU fleet health monitoring)

## Stack

**Languages:** Python · TypeScript · JavaScript · Java · C/C++ · SQL · Bash
**Backend:** FastAPI · Spring Boot · gRPC · Temporal · REST · PostgreSQL · Redis · Kafka · Celery/Taskiq · Elasticsearch · Playwright
**Frontend:** React · TanStack Query · Zustand · Tailwind · React Hook Form/Zod · WebSocket/SSE
**AI/LLM:** RAG/GraphRAG · hybrid retrieval (dense+sparse, reranking) · Qdrant · pgvector · knowledge graphs (Apache AGE) · agent tool-calling (LangChain, MCP) · OpenAI/Gemini APIs · LiteLLM · Langfuse · PyTorch · SGLang (local serving) · Ragas evals
**Cloud/Ops:** AWS (Lambda, DynamoDB, CloudFront) · GCP · Cloudflare Workers · Docker · Kubernetes · Terraform · GitHub Actions · OpenTelemetry · Prometheus · Sentry · on-prem GPU deployment

## Writing

- [Running autonomous AI agents safely — devin-harness teardown](/writing/agents.html)
- [Building a real-time freight risk SaaS](/writing/freightscaler.html)

## Links

- **LinkedIn:** [linkedin.com/in/yunseop-i-207a7215a](https://www.linkedin.com/in/yunseop-i-207a7215a/)
- **Site:** [signalgap9-del.github.io](https://signalgap9-del.github.io)
- **Email:** tristayunsub@gmail.com
