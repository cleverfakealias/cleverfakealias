# Ben Hickman
### AI Engineer · Software Engineer · Applied AI and Distributed Systems

I build production AI agents and the backend systems that support them. My background covers event-driven architecture, data engineering, and applied AI in environments where reliability, latency, and cost matter.

I work as an **AI Engineer** at SPS Commerce on MAX, a customer-facing AI agent. I am going on 15 years in software, with full stack engineering work since 2018 across backend, frontend, and data.

**me@benhickman.dev** · [LinkedIn](https://www.linkedin.com/in/ben-hickman-dev/) · [benhickman.dev](https://www.benhickman.dev) · [zengineer.cloud](https://www.zengineer.cloud)

---

## What I Build

**Production AI Agents**: Customer-facing agents with LangGraph, RAG pipelines, document intelligence, and tool use. I trace them with MLflow and gate releases with evals.

**AI Delivery Pipelines**: Helm charts, CloudFormation templates, and Azure DevOps pipelines that promote an agent through dev, test, and production. Tests and evals are the gates.

**Event-Driven Systems**: Kafka and Confluent Cloud pipelines, async orchestration, service contracts, and backpressure and retry strategies that hold up under load.

**Data Platforms**: Databricks, Delta Lake, and ingestion workflows for batch and streaming, designed with schema evolution in mind.

**AI-Assisted Engineering**: Custom Claude Code hooks and skills for code review, automatic test runs, and formatting. Guardrails block unapproved package installs when an agent runs in auto mode.

---

## Engineering Principles

- **Explicit contracts**: clear interfaces beat clever abstractions
- **Failure-first design**: idempotency, retries, dead-letter queues, circuit breakers
- **Measured AI**: latency and cost budgets, retrieval quality checks, regression gates before promotion
- **Operability**: if it is hard to debug at 2am, it is not done

---

## Core Stack

| Domain | Tools |
|---|---|
| **Languages** | Python, TypeScript, Java |
| **AI / ML** | LangGraph, LangChain, MLflow, OpenAI API, Databricks Model Serving, Hugging Face |
| **AI Coding Tools** | Claude Code, Codex, GitHub Copilot, Google Antigravity |
| **Cloud** | AWS (Lambda, EC2, API Gateway, S3, DynamoDB, RDS, CloudFront, Route 53), Cloudflare Workers, Vercel |
| **Streaming** | Kafka, Confluent Cloud |
| **Data** | Databricks, Delta Lake, PostgreSQL, ChromaDB |
| **Back End** | FastAPI, Flask, Dropwizard |
| **Front End** | Astro, React, Next.js, Vite |
| **Infra** | Helm, Kubernetes, Docker, CloudFormation, Terraform |
| **CI/CD & Observability** | Azure DevOps, GitHub Actions, Jenkins, Grafana, Prometheus |

---

## Selected Work

**MAX: Customer-Facing AI Agent (SPS Commerce)**
Built the agent with a Python and LangGraph backend and a TypeScript chat UI. MAX went live for all SPS Fulfillment customers in September 2026.

**Build and Deploy Pipelines for an AI Agent**
My team owns the MAX pipelines end to end. We write the Helm charts, CloudFormation templates, and Azure DevOps pipelines, with tests and evals as promotion gates.

**Claude Code Hooks and Skills**
Built custom hooks and skills for code review, automatic test runs, and formatting. Added guardrails that block unapproved package installs in auto mode.

**LangGraph Multi-Agent System**
Architected a multi-agent workflow with MLflow tracing. Included tool-call success tracking, latency budgets for each agent, and a retrieval quality evaluation loop.

**Private Document RAG Pipeline**
Built an internal retrieval system for unstructured document search. It covers chunking strategy, an embedding pipeline, ChromaDB retrieval, and a FastAPI layer with response caching and latency guardrails.

**REST + MCP API Layer for LLM Workflows**
Developed MCP-compatible API surfaces that integrate LLM tooling into production services, with auth, rate limiting, and structured error contracts.

**Kafka-Based Ingestion Platform**
Designed and operated event-driven ingestion pipelines on Confluent Cloud for a B2B SaaS product. Handled schema evolution, consumer lag monitoring, and dead-letter processing at scale.

**Databricks Integration (iData / Delta Lake)**
Built the integration layer between a legacy data system and Databricks. It gives reliable Delta Lake writes with idempotent ingestion patterns and lineage tracking.

---

## Currently

- **AI Engineer** at SPS Commerce, working on MAX after its September 2026 release to all SPS Fulfillment customers
- Improving observability for AI execution paths: latency, tool-call success, retrieval quality, and regression detection
- Making software and AI content as [ZennLogic](https://www.zennlogic.com) on YouTube and Twitch

---

## Consulting

Available for contract work through [zengineer.cloud](https://www.zengineer.cloud) and [zendev.pro](https://www.zendev.pro). I take on AI workflow tooling, event-driven architecture, data platform engineering, and website builds with Astro and Cloudflare.

---

<div align="center">

![Stats](https://github-readme-stats.vercel.app/api?username=cleverfakealias&show_icons=true&theme=transparent&hide_border=true&hide_title=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=cleverfakealias&layout=compact&theme=transparent&hide_border=true&hide_title=true)

![Visitors](https://komarev.com/ghpvc/?username=cleverfakealias&color=grey)

</div>
