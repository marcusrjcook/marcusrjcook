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

**AI & LLM**

![Anthropic Claude](https://img.shields.io/badge/Anthropic_Claude-D97706?style=flat-square&logoColor=white)
![OpenAI API](https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logoColor=white)
![Agentic Tool Use](https://img.shields.io/badge/Agentic_Tool_Use-6366F1?style=flat-square&logoColor=white)
![Function Calling](https://img.shields.io/badge/Function_Calling-6366F1?style=flat-square&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-7C3AED?style=flat-square&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B35?style=flat-square&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat-square&logoColor=white)
![Prompt Engineering](https://img.shields.io/badge/Prompt_Engineering-0EA5E9?style=flat-square&logoColor=white)
![Multi-Agent Orchestration](https://img.shields.io/badge/Multi--Agent_Orchestration-0EA5E9?style=flat-square&logoColor=white)
![SSE Streaming](https://img.shields.io/badge/SSE_Streaming-0EA5E9?style=flat-square&logoColor=white)
![Model Evaluation](https://img.shields.io/badge/Model_Evaluation-7C3AED?style=flat-square&logoColor=white)
![RAGAS](https://img.shields.io/badge/RAGAS-7C3AED?style=flat-square&logoColor=white)
![MCP](https://img.shields.io/badge/MCP_(Model_Context_Protocol)-D97706?style=flat-square&logoColor=white)

**Backend**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server_(T--SQL)-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API_Design-6DB33F?style=flat-square&logoColor=white)
![JWT Auth](https://img.shields.io/badge/JWT_Auth-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244C5A?style=flat-square&logoColor=white)

**Data & Messaging**

![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=flat-square&logoColor=white)
![Real-Time Ingestion](https://img.shields.io/badge/Real--Time_Stream_Ingestion-0F172A?style=flat-square&logoColor=white)
![InfluxDB](https://img.shields.io/badge/InfluxDB-22ADF6?style=flat-square&logo=influxdb&logoColor=white)
![TimescaleDB](https://img.shields.io/badge/TimescaleDB-FDB515?style=flat-square&logoColor=black)

**Frontend**

![React](https://img.shields.io/badge/React_18-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)

**DevOps & Cloud**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS_(EC2,_S3)-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

---

## Projects

**[SiteTrack RTLS Dashboard](https://github.com/marcusjco/rtls-dashboard)**
AI-powered RTLS intelligence platform built on the same architecture as a live DoD aviation facility deployment (NDA). 12 SQL-backed agentic AI tools with tool use and function calling, ChromaDB RAG, SSE streaming, JWT auth, RBAC. FastAPI + React/TypeScript. 180 assets, 7 zones, 31,000+ events.

**[LangChain Multi-Tool Agent](https://github.com/marcusjco/langchain-agent-demo)**
LangChain/LangGraph ReAct agent with web search, calculator, and datetime tools. Multi-turn conversation memory via LangGraph MemorySaver checkpointer. SSE streaming. FastAPI backend on AWS EC2.

**[RTLS Operations Automation](https://github.com/marcusjco/rtls-ops-automation)**
39-node n8n multi-agent orchestration workflow. Scheduled shift intelligence pipeline + real-time webhook alert triage. Claude classifying severity and routing to Slack/Gmail/Sheets automatically.

**[Claude Agentic Query Agent](https://claude-agentic-query-agent.onrender.com)** · [Repo](https://github.com/marcusjco/claude-agentic-query-agent)
Live deployed FastAPI service demonstrating multi-turn Claude tool use. History management, structured error recovery, SSE streaming. Running in production on Render.

**[RAG Demo](https://github.com/marcusjco/rag-demo)**
ChromaDB RAG pipeline with sentence-transformer embeddings. Chunking, embedding, semantic retrieval, score filtering. FastAPI + React.

---

Open to AI Engineer and LLM integration roles — remote, hybrid, or onsite.

[linkedin.com/in/marcusrjcook](https://linkedin.com/in/marcusrjcook)
