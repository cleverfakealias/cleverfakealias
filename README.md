# Ben Hickman
### Applied AI Engineer · Distributed Systems

I build production AI systems on top of more than a decade of backend and data engineering. Today that means agentic workflows in LangGraph running on Kubernetes, with Amazon Bedrock for model access and Postgres with pgvector for retrieval.

**me@benhickman.dev** · [LinkedIn](https://www.linkedin.com/in/ben-hickman-02978819b/) · [benhickman.dev](https://www.benhickman.dev) · [zengineer.cloud](https://www.zengineer.cloud)

---

## What I Work On Now

**Agentic workflows.** LangGraph graphs for multi step reasoning and tool use, with explicit state, retries and fallbacks so a bad model call degrades gracefully instead of failing the whole run.

**Retrieval and semantic search.** Postgres with pgvector as the vector store, Cohere Embed v4 for embeddings, and hybrid retrieval that combines vector and keyword search. One database for relational data and vectors keeps the system simple to operate.

**Model access on Bedrock.** Amazon Bedrock as the model layer, with per workflow model choice, cost and latency budgets, and evaluation gates before a prompt or model change ships.

**Running it on Kubernetes.** Containerized agents and APIs deployed to Kubernetes, with the same observability and rollout discipline as any other production service.

## Where I Came From

Before AI engineering I spent years on event driven and data platform work, and that background shapes how I build AI systems.

- **Kafka ingestion on Confluent Cloud** for a B2B SaaS product: schema evolution, consumer lag monitoring and dead letter processing at scale.
- **Databricks and Delta Lake integration**: idempotent ingestion from a legacy data system with lineage across the pipeline.
- **Infrastructure as code**: reusable CloudFormation and Terraform modules for auth, config, ingestion and orchestration.

## Engineering Principles

- **Measured AI.** Evals, latency budgets and cost limits decide what ships, not a good demo.
- **Failure first.** Idempotency, retries, dead letter queues and circuit breakers apply to model calls too.
- **Explicit contracts.** Clear interfaces and typed state beat clever abstractions.
- **Operability.** If it is hard to debug at 2am, it is not done.

## Core Stack

| Domain | Tools |
|---|---|
| **AI and agents** | LangGraph, LangChain, Amazon Bedrock, Cohere Embed v4, MCP |
| **Retrieval** | PostgreSQL, pgvector, hybrid search, rerankers |
| **Platform** | Kubernetes, Docker, AWS, Cloudflare Workers |
| **Languages** | Python, TypeScript, Java |
| **Data and streaming** | Kafka, Confluent Cloud, Databricks, Delta Lake |
| **Infra and delivery** | Terraform, CloudFormation, GitHub Actions |
| **Observability** | Grafana, Prometheus, MLflow |

## Projects

Side projects where I try ideas before they reach work:

- **[zenn_ai](https://github.com/cleverfakealias/zenn_ai)** · Twitch AI chat bot with layered prompt injection defenses, a Python MCP server for game data, and a hardened self hosted deploy.
- **[ZenMind](https://github.com/cleverfakealias/ZenMind)** · Local first RAG over Obsidian notes: hybrid BM25 and vector retrieval, reranking, HyDE retries and an eval harness.
- **[exile-view](https://github.com/cleverfakealias/exile-view)** · Twitch extension on Cloudflare Workers with D1, R2, JWT auth and PKCE OAuth.
- **[jev-sandbox](https://github.com/cleverfakealias/jev-sandbox)** · Evaluating an LLM gate that decides whether a support case is safe to automate.
- **[token-counter](https://github.com/cleverfakealias/token-counter)** · Prices Claude Code usage at API rates from local transcripts. Stdlib Python and SQLite.
- **[agents](https://github.com/cleverfakealias/agents)** · My Claude Code project scaffold: hooks that format, lint, test and guard every agent edit.

## Consulting

Available for contract work through [zengineer.cloud](https://www.zengineer.cloud): agentic systems, RAG and semantic search, and data platform engineering.

---

<div align="center">

![Stats](https://github-readme-stats.vercel.app/api?username=cleverfakealias&show_icons=true&theme=transparent&hide_border=true&hide_title=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=cleverfakealias&layout=compact&theme=transparent&hide_border=true&hide_title=true)

</div>
