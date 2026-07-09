<!-- Profile README for swastik-nandy -->

<div align="center">

# 👋 Hey, I'm Swastik

I spend most of my time making AI agents actually *do things* instead of just talking about them.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Swastik%20Nandy-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/swastik-nandy)
[![Email](https://img.shields.io/badge/Email-swastik.nandy%40outlook.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:swastik.nandy@outlook.com)
[![GitHub](https://img.shields.io/badge/GitHub-swastik--nandy-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/swastik-nandy)

</div>

---

## 🧠 About Me

I'm a Software Engineering Intern at **Embitel Technologies India Private Limited**, a Volkswagen Group company, where I build agentic AI systems and retrieval pipelines that run in actual production, not just in a notebook.

Here's the honest pitch: I don't think of "RAG" and "agents" as two separate things anymore. My whole world is the blend — **agentic loops that reason and re-plan**, **tool calling and MCP-based orchestration** that let agents actually reach out and touch real systems, **retrieval pipelines** that feed those agents grounded context instead of hallucinated vibes, and **model lifecycle management** so the whole thing doesn't rot the moment a model gets swapped or a prompt drifts.

If you've ever built a "RAG chatbot" that's really just embed-and-cosine-similarity with extra steps — I've been there, outgrown that, and now build the version with actual reasoning, actual orchestration, and actual observability behind it.

---

## 🚀 What I Work On

* **Agentic loops** — plan → act → observe → re-plan, with self-correction when retrieval or a tool call comes back wrong
* **Tool calling & MCP** — wiring agents into MCP servers and external tools so they can query, fetch, act, and not just chat
* **Multi-agent orchestration** — planner/executor/critic patterns, routing between agents instead of one giant prompt doing everything
* **RAG pipelines at scale** — chunking, embedding, hybrid dense+sparse search, reranking, on Qdrant
* **Adaptive graph-based retrieval** — going beyond flat vector similarity when context actually needs structure and relationships
* **Model lifecycle management** — versioning, evals, drift detection, rollback, and knowing when a model swap silently breaks your retrieval quality
* **FastAPI backend services** that hold all of the above together and actually ship

---

## 🎯 Right Now I'm

```txt
Building        Agentic RAG systems with tool calling + MCP orchestration
Wiring          Multi-agent loops that self-correct instead of one-shot guessing
Scaling         Retrieval pipelines on Qdrant — hybrid search, reranking, graph-aware context
Managing        Model lifecycle — versioning, evals, drift, rollback
Always          Learning something that makes last month's architecture look naive
```

---

## 🛠️ Tech Stack

### Languages

<p>
  <img src="https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white" />
</p>

### Backend

<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" />
  <img src="https://img.shields.io/badge/Actix-000000?style=for-the-badge&logo=rust&logoColor=white" />
</p>

### Databases & Cache

<p>
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DD0031?style=for-the-badge&logo=redis&logoColor=white" />
</p>

### Agentic AI / RAG / Orchestration

<p>
  <img src="https://img.shields.io/badge/Agentic%20Loops-Plan--Act--Observe-7B61FF?style=for-the-badge" />
  <img src="https://img.shields.io/badge/MCP-Tool%20Calling-7B61FF?style=for-the-badge" />
  <img src="https://img.shields.io/badge/LangGraph-Multi--Agent%20Orchestration-1C3C3C?style=for-the-badge" />
  <img src="https://img.shields.io/badge/RAG-Hybrid%20Retrieval-7B61FF?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge&logo=qdrant&logoColor=white" />
  <img src="https://img.shields.io/badge/Pinecone-000000?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Model%20Lifecycle-Evals%20%26%20Versioning-blueviolet?style=for-the-badge" />
</p>

### Tools & Infrastructure

<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05033?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
</p>

---

## 🧩 Where I Spend My Time

```txt
Agentic AI            Reasoning loops · Multi-agent orchestration · Tool calling · MCP integration
RAG Engineering       Chunking · Embedding · Hybrid search · Reranking · Graph-aware retrieval
Model Lifecycle       Versioning · Evals · Drift detection · Rollback strategy
Backend Engineering   FastAPI · APIs · Databases · Caching · Deployment
Data Engineering      Ingestion pipelines for messy, real-world enterprise data
```

---

## 🏗️ What I'm Building — Embitel Technologies (Volkswagen Group)

### Agentic RAG Platform

This is the main thing I pour my energy into. It's not "a chatbot with a vector DB" — it's an actual agentic system:

* **Agentic loops** that plan a retrieval strategy, execute it, look at what came back, and re-plan if the context is thin or wrong
* **Tool calling + MCP** so agents can reach beyond the vector store — query live systems, call internal tools, fetch structured data on demand
* **Multi-agent orchestration** splitting work across planner, retriever, and executor roles instead of cramming everything into one prompt
* **Adaptive graph-based backend** for retrieval that understands relationships, not just cosine similarity
* **Hybrid dense + sparse search on Qdrant**, with reranking layered on top for actual precision
* **Model lifecycle management** wrapped around all of it — because none of the above matters if you can't tell when a model swap quietly tanked your retrieval quality

### AI Backend Systems

The infrastructure that makes the above possible without falling over:

* FastAPI services gluing agents, tools, and retrieval together
* Self-correcting pipelines with feedback-driven query rewriting when retrieval misses
* Semantic caching so I'm not re-embedding or re-calling tools for the same thing twice
* Data engineering pipelines built to swallow messy real-world enterprise data without breaking

---

## 📌 How I Think About Engineering

* An agent that can't call a tool or hit an MCP server is just a chatbot wearing a trench coat
* RAG without reranking is basically retrieval roulette
* If you can't tell when your model version changed and quality dropped, you don't have a system — you have a hope
* Graph-aware retrieval beats flat vector similarity the second context actually has structure
* Build things understandable and testable first — clever comes later, if at all
* Don't hard-code business logic into pipelines that are supposed to generalize

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=swastik-nandy&show_icons=true&theme=tokyonight&hide_border=true" height="170" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=swastik-nandy&layout=compact&theme=tokyonight&hide_border=true" height="170" />

</div>

---

## 🔥 GitHub Streak

<div align="center">

<img src="https://streak-stats.demolab.com?user=swastik-nandy&theme=tokyonight&hide_border=true" />

</div>

---

## 💬 Ask Me About

* Agentic loops — how to make an agent actually reason and re-plan instead of one-shotting
* Tool calling and MCP — wiring agents into real external systems
* Multi-agent orchestration patterns
* RAG pipelines that actually hold up at scale (hybrid search, reranking, graph retrieval)
* Model lifecycle management — versioning, evals, drift, rollback
* FastAPI backend architecture for AI-heavy systems

---

## 🌐 Let's Connect

<p>
  <a href="https://www.linkedin.com/in/swastik-nandy">
    <img src="https://img.shields.io/badge/LinkedIn-Swastik%20Nandy-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:swastik.nandy@outlook.com">
    <img src="https://img.shields.io/badge/Email-Contact%20Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://github.com/swastik-nandy">
    <img src="https://img.shields.io/badge/GitHub-swastik--nandy-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

---

<div align="center">

### ⚙️ Building agents that plan, call tools, retrieve, and actually get it right

</div>
