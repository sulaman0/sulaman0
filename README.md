<div align="center">
	<img alt="Sulaman Khan" src="https://readme-typing-svg.demolab.com/?lines=AI+Engineer+%7C+LLM+%7C+RAG+%7C+Agents+%7C+MCP;8+Years+Production+Software+Engineering;Go+%7C+Python+%7C+Node.js+%7C+Rust&center=true&width=620&height=55">
</div>

<p align="center">
	<a href="https://www.linkedin.com/in/suleman-khan-eng/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
	<a href="https://stackoverflow.com/users/8344330/mr-sulaman-khan" target="_blank"><img src="https://img.shields.io/badge/Stack%20Overflow-F58025?style=for-the-badge&logo=stack-overflow&logoColor=white" /></a>
	<a href="mailto:se.sulaman.khan@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p><br>

## ⚡ About Me

I'm an **AI Engineer with 8 years of production software experience**, focused on building **Large Language Model (LLM) applications** — the systems companies actually ship, not demos.

I build **Retrieval-Augmented Generation (RAG) pipelines**, **LLM agents** with tool calling, **Model Context Protocol (MCP)** integrations, structured-output extraction systems, and **computer-vision pipelines** (object detection, OCR, face recognition). My work emphasizes what most AI tutorials skip — reliability, multi-tenant security, evaluation, cost control, and graceful failure.

That discipline comes from years building **fintech platforms** (processing $1M+ in transactions), **high-traffic systems** (100,000+ daily active users, an API tuned to 1M+ requests), and **Layer 1 blockchain infrastructure**. I already know how to ship secure, scalable systems — I apply that same rigor to the AI layer.

> **The AI is learnable in months; the engineering judgment took 8 years. I bring both.**

🌍 **Open to remote roles** — full overlap with **Gulf** hours, 3–4 hours with **UK & Europe** every afternoon, **US mornings** covered. Contract or full-time.

> **On code visibility:** production work for client engagements lives in client-owned repositories. The AI repos below are public **architecture write-ups** — design decisions, failure modes, and what I'd do differently — rather than client code.

---

## 🤖 AI Projects

#### 🔎 [Multi-Tenant RAG Service](https://github.com/sulaman0/multi-tenant-rag-service)
Production RAG API built with **Python, FastAPI, ChromaDB, and Ollama**. Token streaming via Server-Sent Events, tenant-isolated retrieval enforced at query time rather than post-filtered, cost/latency observability middleware, and provider-failure handling. The write-up covers how the isolation property is actually tested — near-identical embeddings across tenants, so the vector store has every reason to confuse them.

#### 🔌 [MCP Server & Client](https://github.com/sulaman0/mcp-server-and-client)
Both halves of a **Model Context Protocol** integration — a server exposing tools and resources, and a client that discovers and calls them at runtime, wired into a local-model agent loop. Building both sides is what surfaces the real design questions: tool descriptions as prompts, server-side validation, and errors written for a model to act on rather than a human to read.

#### 🧠 [Agentic System (ReAct)](https://github.com/sulaman0/react-agent-loop)
An LLM agent with a **think → act → observe** tool-calling loop, step-limit safety caps, and schema validation at the tool boundary. Implemented in raw orchestration **and** rebuilt in **LangGraph** — with an honest account of what the framework bought and what it cost.

#### 🎫 [Support Ticket Triage Engine](https://github.com/sulaman0/support-ticket-triage-engine)
LLM system that classifies priority, extracts structured fields, and drafts replies from raw tickets. The engineering is in the degradation path: `needs_human` as a first-class outcome rather than an error state, because a confident wrong classification is worse than an explicit "I don't know."

#### 🛒 [Retail Shelf Detection & Recognition](https://github.com/sulaman0/retail-shelf-detection)
Computer-vision pipeline integrating **YOLO** for shelf and product detection, **OCR** for on-shelf text extraction, and **ArcFace** for face recognition. Where multi-model pipelines actually break: error compounds multiplicatively, and detection crops are hostile input to OCR.

#### 🧾 [ZATCA Phase 2 E-Invoicing](https://github.com/sulaman0/zacta-phase2)
Saudi Arabia e-invoicing compliance implementation (Fatoora, XML generation, certificate signing) — direct experience with Kingdom of Saudi Arabia regulatory requirements. Open-sourced and in use by other teams (⭐ 13 · 🍴 7).

---

## 🎯 Engineering Highlights

- **AI Systems:** RAG pipelines, agents, and MCP integrations built with production concerns — evaluation harnesses (retrieval hit-rate + faithfulness), multi-provider abstraction (Anthropic Claude, OpenAI, Ollama), and defensive structured-output parsing.
- **Performance at Scale:** Migrated a high-traffic **Node.js** service serving **1M users to Go**, resolving memory issues that had been managed with scheduled restarts.
- **Optimized API Performance:** Refined a blockchain art API to handle **1M+ requests** through careful server-resource management.
- **High-Traffic Systems:** Scaled a CMS platform to **100,000+ daily active users**; cut operational costs **40%** moving to serverless on AWS Lambda.
- **Technical Leadership:** Led projects to **CMMI 2.0** certification; optimized startup times to 10 seconds; elevated an app rating from **4.3 ★ to 4.9 ★**.
- **Fintech:** Delivered secure transaction, authentication, and fraud-prevention features for a fintech app processing **$1M+** in its first quarter.

---

## 🛠️ Tech Stack

| **Category** | **Technologies** |
|-------------|-----------------|
| **AI / LLM** | ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white) ![LangGraph](https://img.shields.io/badge/LangGraph-FF6F61?style=for-the-badge&logo=chainlink&logoColor=white) ![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white) ![Anthropic](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white) ![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white) |
| **AI Infra** | ![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B6B?style=for-the-badge&logoColor=white) ![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=for-the-badge&logo=postgresql&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white) ![MCP](https://img.shields.io/badge/MCP-000000?style=for-the-badge&logoColor=white) |
| **Computer Vision** | ![YOLO](https://img.shields.io/badge/YOLO-00FFFF?style=for-the-badge&logoColor=black) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white) ![OCR](https://img.shields.io/badge/OCR-4285F4?style=for-the-badge&logoColor=white) |
| **Languages** | ![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white) ![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black) ![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white) |
| **Databases** | ![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white) ![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white) ![ElasticSearch](https://img.shields.io/badge/-ElasticSearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white) |
| **Cloud & DevOps** | ![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white) ![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white) ![DigitalOcean](https://img.shields.io/badge/DigitalOcean-%230167ff.svg?style=for-the-badge&logo=digitalOcean&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white) |
| **Blockchain** | ![Substrate](https://img.shields.io/badge/Substrate-282828?style=for-the-badge&logo=substrate&logoColor=white) ![Solidity](https://img.shields.io/badge/Solidity-363636?style=for-the-badge&logo=solidity&logoColor=white) ![GraphQL](https://img.shields.io/badge/-GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white) |

---

## 🔗 Layer 1 & Product Engineering

Core engineer on a live Layer 1 chain and the full product surface around it — the backend and protocol depth that underpins my production engineering discipline:

- [**⛓️ Elysium Chain**](https://elysiumchain.tech/) — Layer 1 blockchain (Substrate + Frontier EVM compatibility layer) for AI, gaming, and metaverse projects. Aura consensus configuration, validator-set and node-authorization pallets, load testing and gas-limit tuning.
- [**🔍 Elysium Scan**](https://explorer.elysiumchain.tech) — Real-time blockchain explorer for transactions, blocks, and accounts.
- [**💼 Elysium CloudWallet**](http://wallet.elysiumchain.tech) — Web3 wallet for managing digital assets.
- [**🎨 Elysium AI NFT Studio**](https://studio-dev.elysiumchain.tech) — No-code AI NFT generation and launch platform.
- [**⚙️ PoS Consensus in Go**](https://github.com/sulaman0/pos-consensus-go) — Proof-of-stake consensus from scratch: stake-weighted leader selection, block proposal, cross-node validation.
- [**🛒 Shopify Apps**](https://apps.shopify.com/care-cart) — Cartly, Sales Pop-up, and Wheelify — used by thousands of merchants.

---

## 📧 Contact

- **Email:** [se.sulaman.khan@gmail.com](mailto:se.sulaman.khan@gmail.com)
- **LinkedIn:** [sulaman-khan](https://www.linkedin.com/in/suleman-khan-601ab9137/)
- **WhatsApp:** [Click to chat](https://wa.me/923167852626)

<!--
  STATS: keep this ONLY if the graph looks healthy. Open your profile logged out and look at it.
  A flat or sparse activity graph advertises a weakness — better to have no graph than a thin one.
  Note that commits attributed to your work account will NOT appear here.
-->
<a href="http://www.github.com/sulaman0"><img src="https://github-readme-activity-graph.vercel.app/graph?username=sulaman0&bg_color=1c1917&color=ffffff&line=0891b2&point=ffffff&area_color=1c1917&area=true&hide_border=true&custom_title=GitHub%20Commits%20Graph" alt="GitHub Commits Graph" /></a>
