<div align="center">

# 🧠 Complete RAG Bootcamp

### *Master Retrieval-Augmented Generation from Zero to Production*

[![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![LangChain](https://img.shields.io/badge/LangChain-v0.3%2B-1C3C3C?style=for-the-badge&logo=chainlink&logoColor=white)](https://www.langchain.com/)
[![LangGraph](https://img.shields.io/badge/LangGraph-Agentic-FF6B6B?style=for-the-badge&logo=graphql&logoColor=white)](https://www.langchain.com/langgraph)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)

<br/>

> **A comprehensive, hands-on bootcamp covering every aspect of Retrieval-Augmented Generation (RAG) —**
> **from fundamentals to cutting-edge agentic architectures, multimodal systems, and production-ready deployment.**

<br/>

```
📚 25 Modules  ·  🛠️ Hands-On Projects  ·  🤖 Agentic AI  ·  🚀 End-to-End Project
```

</div>

---

## 📖 What is RAG?

**Retrieval-Augmented Generation (RAG)** is a technique that enhances Large Language Models (LLMs) by grounding their responses in real, up-to-date, and domain-specific knowledge retrieved from external sources. Instead of relying solely on parametric knowledge baked into model weights, RAG systems:

1. 🔍 **Retrieve** relevant documents from a knowledge base
2. 🧩 **Augment** the LLM prompt with that retrieved context
3. 💬 **Generate** accurate, grounded, and factual responses

RAG is the backbone of modern enterprise AI applications — powering intelligent chatbots, document search engines, and autonomous AI agents.

---

## 🗂️ Course Curriculum

### 🟢 Foundations

| # | Module | Topics Covered |
|---|--------|---------------|
| 01 | [📘 Introduction to RAG](./01-INTRODUCTION%20TO%20RAG/) | RAG fundamentals, architecture overview, business impact |
| 02 | [💾 Data Ingestion & Parsing](./02-DATA%20INGESTION%20%26%20PARSING/) | PDF, HTML, CSV loaders; document parsers; preprocessing pipelines |
| 03 | [🔢 Vector Embedding & Databases](./03-VECTOR%20EMBEDDING%20%26%20DATABASES/) | Embedding models, semantic similarity, vector space theory |
| 04 | [🗄️ Vector Stores & Databases](./04-VECTOR%20STORES%20%26%20DATABASES/) | FAISS, Chroma, Pinecone, Weaviate — deep dive & comparison |
| 05 | [✂️ Advanced Chunking & Preprocessing](./05-ADVANCED%20CHUNKING%20%26%20PREPROCESSING%20TECHNIQUES/) | Recursive, semantic, sentence-window chunking strategies |

### 🔵 Intermediate — Search & Query

| # | Module | Topics Covered |
|---|--------|---------------|
| 06 | [🔀 Hybrid Search Strategies](./06-HYBRID%20SEARCH%20STRATEGIES/) | BM25 + dense retrieval, reciprocal rank fusion |
| 07 | [🔍 Query Enhancement](./07-QUERY%20ENHANCEMENT/) | HyDE, query rewriting, multi-query retrieval, step-back prompting |
| 08 | [🖼️ Multimodal RAG](./08-MULTIMODAL%20RAG/) | Image + text retrieval, vision-language models, multimodal embeddings |

### 🟣 Advanced — Agentic AI

| # | Module | Topics Covered |
|---|--------|---------------|
| 09 | [🤖 AI Agents & Agentic AI](./09-AI%20AGENTS%20%26%20AGENTIC%20AI/) | Agent fundamentals, ReAct, tool use, planning loops |
| 10 | [⛓️ LangChain Hands-On (v1)](./10-UPDATED%20LANGCHAIN%20HANDS-ON%20WITH%20VERSION%20V1/) | Updated LangChain v0.3+ patterns, LCEL, runnables |
| 11 | [🕸️ LangGraph Basics](./11-LANGGRAPH%20BASICS/) | State machines, graph nodes, edges, conditional routing |
| 12 | [🏗️ Agents Architecture](./12-AGENTS%20ARCHITECTURE/) | Multi-agent design patterns, supervisor-worker architecture |
| 13 | [🔁 Agentic RAG](./13-AGENTIC%20RAG/) | RAG inside agents, tool-calling retrievers |
| 14 | [🧭 Autonomous RAG](./14-AUTONOMOUS%20RAG/) | Self-routing, reflection, iterative retrieval |
| 15 | [👥 Multi-Agents RAG](./15-MULTI%20AGENTS%20RAG/) | Collaborative agents, task decomposition |

### 🔴 Expert — Production-Grade RAG

| # | Module | Topics Covered |
|---|--------|---------------|
| 16 | [🛠️ Corrective RAG](./16-CORRECTIVE%20RAG/) | Document grading, hallucination detection, web fallback |
| 17 | [🔄 Adaptive RAG](./17-ADAPTIVE%20RAG/) | Query routing, adaptive retrieval strategies |
| 18 | [💾 RAG with Persistent Memory](./18-RAG%20WITH%20PERSISTENT%20MEMORY/) | Conversation history, long-term memory, episodic memory |
| 19 | [⚡ Cache RAG with LangGraph](./19-CACHE%20RAG%20WITH%20LANGGRAPH/) | Semantic caching, cost reduction, latency optimization |
| 20 | [📄 Vectorless RAG with Page Index](./20-VECTORLESS%20RAG%20WITH%20PAGE%20INDEX/) | BM25-only retrieval, page-level indexing |
| 21 | [🛡️ Guardrails](./21-GAURDRAILS/) | Input/output filtering, toxicity, PII redaction, safety layers |
| 22 | [🚪 LLM Gateways](./22-LLM%20GATEWAYS/) | API routing, load balancing, cost monitoring, model fallback |
| 23 | [📊 Chatbot & RAG Evaluation](./23-CHATBOT%20%26%20RAG%20EVALUATION/) | RAGAS, faithfulness, context precision, answer relevancy |
| 24 | [🕸️ Graph DB Practical Implementation](./24-GRAPH%20DB%20PRACTICAL%20IMPLEMENTATION/) | Neo4j, knowledge graphs, GraphRAG |
| 25 | [🚀 End-to-End RAG Document Search Project](./25-END%20TO%20END%20RAG%20DOCUMENT%20SEARCH%20PROJECT/) | Full-stack RAG app: ingestion → retrieval → generation → UI |

---

## 🛠️ Tech Stack

<div align="center">

| Category | Technologies |
|----------|-------------|
| **LLM Frameworks** | LangChain, LangGraph, LlamaIndex |
| **LLM Providers** | OpenAI GPT-4, Anthropic Claude, Google Gemini, Ollama |
| **Vector Stores** | FAISS, Chroma, Pinecone, Weaviate, Qdrant |
| **Graph Databases** | Neo4j, NetworkX |
| **Embeddings** | OpenAI, HuggingFace Sentence-Transformers, Cohere |
| **Data Parsing** | PyPDF2, Unstructured, LlamaParse, BeautifulSoup |
| **Evaluation** | RAGAS, DeepEval, LangSmith |
| **Deployment** | FastAPI, Streamlit, Docker |

</div>

---

## 🚀 Getting Started

### Prerequisites

```bash
# Python 3.10 or higher
python --version

# Install pip
pip install --upgrade pip
```

### Clone the Repository

```bash
git clone https://github.com/Suraj-G-Rao/Complete-RAG-Bootcamp.git
cd Complete-RAG-Bootcamp
```

### Set Up Environment

```bash
# Create virtual environment
python -m venv venv

# Activate (Windows)
venv\Scripts\activate

# Activate (Mac/Linux)
source venv/bin/activate

# Install dependencies (per module)
pip install -r requirements.txt
```

### Configure API Keys

```bash
# Create .env file
cp .env.example .env

# Add your keys
OPENAI_API_KEY=your_openai_key
ANTHROPIC_API_KEY=your_anthropic_key
GOOGLE_API_KEY=your_google_key
PINECONE_API_KEY=your_pinecone_key
```

---

## 📂 Repository Structure

```
Complete-RAG-Bootcamp/
│
├── 01-INTRODUCTION TO RAG/              # RAG fundamentals & PDFs
├── 02-DATA INGESTION & PARSING/         # Loaders, parsers, pipelines
├── 03-VECTOR EMBEDDING & DATABASES/     # Embeddings deep dive
├── 04-VECTOR STORES & DATABASES/        # FAISS, Chroma, Pinecone
├── 05-ADVANCED CHUNKING.../             # Chunking strategies
├── 06-HYBRID SEARCH STRATEGIES/         # BM25 + dense retrieval
├── 07-QUERY ENHANCEMENT/                # Query optimization
├── 08-MULTIMODAL RAG/                   # Images + text
├── 09-AI AGENTS & AGENTIC AI/           # Agent fundamentals
├── 10-UPDATED LANGCHAIN.../             # LangChain v0.3+
├── 11-LANGGRAPH BASICS/                 # Graph-based agents
├── 12-AGENTS ARCHITECTURE/              # Multi-agent patterns
├── 13-AGENTIC RAG/                      # Agents + RAG
├── 14-AUTONOMOUS RAG/                   # Self-directed RAG
├── 15-MULTI AGENTS RAG/                 # Collaborative agents
├── 16-CORRECTIVE RAG/                   # Self-correcting pipelines
├── 17-ADAPTIVE RAG/                     # Dynamic routing
├── 18-RAG WITH PERSISTENT MEMORY/       # Memory-enhanced RAG
├── 19-CACHE RAG WITH LANGGRAPH/         # Semantic caching
├── 20-VECTORLESS RAG WITH PAGE INDEX/   # BM25-only RAG
├── 21-GAURDRAILS/                       # Safety & filtering
├── 22-LLM GATEWAYS/                     # API management
├── 23-CHATBOT & RAG EVALUATION/         # RAGAS evaluation
├── 24-GRAPH DB PRACTICAL.../            # Knowledge graphs
├── 25-END TO END RAG PROJECT/           # Full production app
│
├── LICENSE
└── README.md
```

---

## 🎯 Learning Path

```
Beginner ──────────────────────────────────────────────► Expert
   │                                                        │
[01-05]          [06-09]         [10-15]          [16-25]
Foundations   Search & Query   Agentic AI     Production RAG
   │                │               │               │
 RAG Basics    Hybrid Search   LangGraph       Guardrails
 Embeddings    Query Rewrite   Multi-Agents    Evaluation
 Chunking      Multimodal      Autonomous      Graph DBs
 Vector DBs    Techniques      Systems         Full Project
```

---

## 🏆 Key Projects

### 🔍 End-to-End RAG Document Search System
> **Module 25** — Build a full-stack intelligent document search application
- Multi-format document ingestion (PDF, DOCX, HTML)
- Hybrid retrieval (dense + sparse)
- LLM-powered answer generation with citations
- Streamlit UI + FastAPI backend
- Evaluation with RAGAS metrics

### 🤖 Multi-Agent RAG Pipeline
> **Modules 12–15** — Orchestrate multiple specialized agents
- Supervisor → Worker architecture using LangGraph
- Agents for retrieval, reasoning, synthesis, and validation
- Adaptive routing based on query complexity

### 🛡️ Production-Ready RAG with Guardrails
> **Modules 21–23** — Enterprise-grade safety & evaluation
- Input/output safety filtering
- PII redaction and content moderation
- Automated quality evaluation with RAGAS

---

## 📈 What You'll Learn

After completing this bootcamp, you will be able to:

- ✅ Build **production-grade RAG pipelines** from scratch
- ✅ Implement **advanced retrieval strategies** (hybrid, multimodal, graph-based)
- ✅ Design **agentic AI systems** using LangGraph and multi-agent architectures
- ✅ Apply **self-corrective and adaptive RAG** patterns
- ✅ Add **guardrails, caching, and gateways** for enterprise deployments
- ✅ **Evaluate RAG quality** using RAGAS and custom metrics
- ✅ Deploy **end-to-end AI applications** with FastAPI and Streamlit

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m 'Add amazing feature'`
4. Push to the branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

<div align="center">

### ⭐ Star this repo if you find it useful!

**Made with ❤️ for the AI community**

[![GitHub stars](https://img.shields.io/github/stars/Suraj-G-Rao/Complete-RAG-Bootcamp?style=social)](https://github.com/Suraj-G-Rao/Complete-RAG-Bootcamp/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/Suraj-G-Rao/Complete-RAG-Bootcamp?style=social)](https://github.com/Suraj-G-Rao/Complete-RAG-Bootcamp/network/members)

</div>