# Ben Hickman
### Founder · Software Engineer — Distributed Systems & Applied AI

I build production-grade backend infrastructure and AI-powered systems. My background spans event-driven architecture, data engineering, and applied ML — usually in environments where reliability, latency, and cost actually matter.

Currently working as an **AI Engineer**, building LLM-powered workflows and evaluation infrastructure on top of a decade of distributed systems experience.

**me@benhickman.dev** · [LinkedIn](https://www.linkedin.com/in/ben-hickman-02978819b/) · [benhickman.dev](https://www.benhickman.dev) · [zengineer.cloud](https://www.zengineer.cloud)

---

## What I Build

**Event-Driven Systems** — Kafka/Confluent Cloud pipelines, async orchestration, service-to-service contracts, backpressure and retry strategies that hold up under load.

**Data Platforms** — Databricks, Delta Lake, and ingestion workflows that go from raw to reliable. Designed for both batch and streaming with schema evolution in mind.

**AI-Enabled Features** — Multi-agent systems with LangGraph, RAG pipelines, document intelligence, and tool-using automation. Tracked with MLflow, evaluated with real evals (not vibes).

**Production Infrastructure** — Lambda/EC2/API Gateway + CloudFormation/Terraform, CI/CD guardrails, Grafana/Prometheus observability, safe deploys. I'm the one who cares about the rollback story.

---

## Engineering Principles

- **Explicit contracts** — clear interfaces beat clever abstractions every time
- **Failure-first design** — idempotency, retries, dead-letter queues, circuit breakers
- **Measured AI** — latency/cost budgets, retrieval quality checks, regression gates before promotion
- **Operability** — if it's hard to debug at 2am, it's not done

---

## Core Stack

| Domain | Tools |
|---|---|
| **Languages** | Python, Java, TypeScript |
| **Cloud (AWS)** | Lambda, EC2, API Gateway, S3, DynamoDB, RDS, CloudFront, Route 53 |
| **Streaming** | Kafka, Confluent Cloud |
| **Data** | Databricks, Delta Lake, PostgreSQL, ChromaDB |
| **AI / ML** | LangGraph, LangChain, OpenAI API, Databricks Model Serving, MLflow, Hugging Face |
| **Back End** | FastAPI, Flask, Dropwizard |
| **Front End** | React, Next.js, Vite |
| **Infra** | CloudFormation, Terraform, Docker, Kubernetes |
| **CI/CD & Observability** | GitHub Actions, Azure Pipelines, Jenkins, Grafana, Prometheus |

---

## Selected Work

**Kafka-Based Ingestion Platform**
Designed and operated event-driven ingestion pipelines on Confluent Cloud for a B2B SaaS product. Handled schema evolution, consumer group lag monitoring, and dead-letter processing at scale.

**Databricks Integration (iData / Delta Lake)**
Built the integration layer between a legacy data system and Databricks, enabling reliable Delta Lake writes with idempotent ingestion patterns and lineage tracking across the pipeline.

**LangGraph Multi-Agent System**
Architected a multi-agent workflow using LangGraph with MLflow tracing for observability. Included tool-call success tracking, per-agent latency budgets, and a retrieval quality evaluation loop.

**Private Document RAG Pipeline**
Built an internal retrieval system for unstructured document search: chunking strategy, embedding pipeline, ChromaDB retrieval, and a FastAPI layer with response caching and latency guardrails.

**REST + MCP API Layer for LLM Workflows**
Developed MCP-compatible API surfaces to integrate LLM tooling into production services, with auth, rate limiting, and structured error contracts.

**IaC-First Service Delivery**
Templated CloudFormation/Terraform modules (auth, config, ingestion, orchestration) reusable across services — reduced per-service bootstrap time and drift between environments.

---

## Currently

- **AI Engineer** (May 2026) — building hybrid LLM workflows with evaluation infrastructure, fallback strategies, and cost controls across Bedrock + OpenAI
- Developing reusable service modules to scale delivery without per-project rewrites
- Improving observability for AI execution paths: latency, tool-call success, retrieval quality, and regression detection

---

## Consulting

Available for contract work through [zengineer.cloud](https://www.zengineer.cloud) and [zendev.pro](https://www.zendev.pro) — event-driven architecture, AI workflow tooling, and data platform engineering.

---

<div align="center">

![Stats](https://github-readme-stats.vercel.app/api?username=cleverfakealias&show_icons=true&theme=transparent&hide_border=true&hide_title=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=cleverfakealias&layout=compact&theme=transparent&hide_border=true&hide_title=true)

![Visitors](https://komarev.com/ghpvc/?username=cleverfakealias&color=grey)

</div>
