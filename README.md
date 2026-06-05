# Marcus Cook — AI Engineer

I build production-ready AI systems: agentic pipelines, RAG architectures, and the real-time data infrastructure that keeps them running.

My production work is under NDA. For the last year and a half I've been building an end-to-end AI pipeline for an enterprise RTLS platform deployed at an active DoD aviation facility — an agentic system with 12 SQL-backed tools and function calling, ChromaDB RAG pipeline for operational context retrieval, and multi-source real-time data ingestion (BLE, MQTT, RFID) serving clients including Pratt & Whitney.

---

## What I Build

**Agentic AI Systems**
Multi-turn LLM pipelines with tool use and function calling. History management preserving tool_use/tool_result pairs. Structured error recovery. ReAct pattern implementation. Built on the Anthropic Claude API and OpenAI API with patterns that transfer across providers.

**RAG Pipelines**
Vector store architecture with ChromaDB and Pinecone. Semantic chunking and embedding. Similarity retrieval with score filtering. Hybrid search patterns. Context injection into LLM prompts. Evaluated with RAGAS — faithfulness, context recall, answer relevancy.

**Multi-Agent Orchestration**
LangChain and LangGraph agent workflows. 39-node n8n orchestration with two independent pipelines: scheduled intelligence reports and real-time webhook-triggered alert triage. Claude handling severity classification and automated routing.

**Real-Time Data Pipelines**
Multi-source ingestion from Quuppa BLE, Kinexon MQTT, and ATR7000 RFID into a unified data model. Apache Kafka consumer pipelines. Designed for correctness and idempotency under high-frequency write load.

---

## Tech Stack

**AI & LLM:** Anthropic Claude API · OpenAI API · LangChain · LangGraph · Agentic Tool Use · Function Calling · RAG · ChromaDB · Pinecone · Prompt Engineering · Multi-Agent Orchestration · SSE Streaming · Model Evaluation · RAGAS · MCP (Model Context Protocol)

**Backend:** Python · FastAPI · SQLAlchemy · Node.js · SQL Server (T-SQL) · SQLite · REST API Design · JWT Auth · gRPC

**Data & Messaging:** Apache Kafka · MQTT · Real-Time Stream Ingestion · Multi-Source Pipeline Architecture · InfluxDB · TimescaleDB

**Frontend:** React 18 · TypeScript · Tailwind CSS · Angular

**DevOps & Cloud:** Docker · AWS (EC2, S3) · Azure · Git · n8n · Render · Kubernetes · Prometheus · Grafana

---

## Projects

**[SiteTrack RTLS Dashboard](https://github.com/marcusjco/rtls-dashboard)**
AI-powered RTLS intelligence platform built on the same architecture as a live DoD aviation facility deployment (NDA). 12 SQL-backed agentic AI tools with tool use and function calling, ChromaDB RAG, SSE streaming, JWT auth, RBAC. FastAPI + React/TypeScript. 180 assets, 7 zones, 31,000+ events.

**[RTLS Operations Automation](https://github.com/marcusjco/rtls-ops-automation)**
39-node n8n multi-agent orchestration workflow. Scheduled shift intelligence pipeline + real-time webhook alert triage. Claude classifying severity and routing to Slack/Gmail/Sheets automatically.

**[Claude Agentic Query Agent](https://claude-agentic-query-agent.onrender.com)** · [Repo](https://github.com/marcusjco/claude-agentic-query-agent)
Live deployed FastAPI service demonstrating multi-turn Claude tool use. History management, structured error recovery, SSE streaming. Running in production on Render.

**[RAG Demo](https://github.com/marcusjco/rag-demo)**
ChromaDB RAG pipeline with sentence-transformer embeddings. Chunking, embedding, semantic retrieval, score filtering. FastAPI + React.

---

Open to AI Engineer and LLM integration roles. Florida-based, open to remote.

[linkedin.com/in/marcusrjcook](https://linkedin.com/in/marcusrjcook)
