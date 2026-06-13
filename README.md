# 🏥 MediAssist AI

### Enterprise Healthcare Agentic AI Copilot

MediAssist AI is an enterprise-grade healthcare AI copilot designed to assist healthcare professionals by combining Generative AI, Retrieval-Augmented Generation (RAG), multi-agent workflows, multimodal AI, and enterprise data integration.

The system aims to provide a unified platform where users can interact with hospital knowledge bases, analyze medical documents, retrieve structured patient information, and generate contextual, AI-powered responses.

---

## 🚀 Features

### Current Implementation

* Streamlit frontend
* FastAPI backend
* Enterprise document organization
* PDF ingestion pipeline
* Multi-document loading
* Modular project architecture

### Planned Features

* Retrieval-Augmented Generation (RAG)
* Vector database integration (FAISS/ChromaDB)
* Multi-agent orchestration using LangGraph
* PostgreSQL integration through MCP
* Medical image understanding
* LLM-powered reasoning
* Response evaluation and guardrails
* Docker containerization
* Azure deployment

---

## 🛠️ Tech Stack

| Layer           | Technology     |
| --------------- | -------------- |
| Frontend        | Streamlit      |
| Backend         | FastAPI        |
| AI Framework    | LangChain      |
| Agent Framework | LangGraph      |
| Vector Database | FAISS          |
| Embeddings      | Hugging Face   |
| Database        | PostgreSQL     |
| MCP             | MCP Python SDK |
| Vision Models   | BLIP / LLaVA   |
| LLM             | OpenAI / Groq  |
| Deployment      | Docker & Azure |

---

## 📂 Project Structure

```
MediAssistAI/

├── frontend/
├── backend/
├── rag/
├── agents/
├── database/
├── mcp_server/
├── multimodal/
├── evaluation/
├── data/
│   ├── pdfs/
│   ├── docs/
│   ├── txt/
│   └── images/
├── configs/
├── tests/
└── README.md
```

---

## 🔄 Workflow

1. User interacts with the Streamlit application.
2. FastAPI receives and processes the request.
3. LangGraph coordinates the required AI agents.
4. Enterprise documents are retrieved from the vector database.
5. Structured hospital data is accessed through PostgreSQL via MCP.
6. Vision models process uploaded medical images when required.
7. The LLM combines all available context and generates a response.
8. The Evaluation Agent validates the response for quality and safety.
9. The final response is delivered to the user.

---

## 📚 Data Sources

The system is designed to work with:

### Unstructured Data

* Hospital SOPs
* Compliance documents
* Operational guidelines
* Discharge summaries

### Structured Data

* Patient records
* Appointments
* Billing
* Lab results
* Insurance information

### Multimodal Data

* Prescription images
* Medical reports
* Lab report screenshots

---

## 📈 Project Status

### ✅ Completed

* Project setup
* Streamlit frontend
* FastAPI backend
* Enterprise data organization
* PDF ingestion pipeline
* Multi-document loading

### 🚧 In Progress

* Document chunking
* Embedding generation
* Vector indexing

### 🔜 Upcoming

* Enterprise RAG
* MCP integration
* Multi-agent orchestration
* Multimodal AI
* Evaluation framework
* Dockerization
* Azure deployment

---

## 🎯 Objective

The goal of MediAssist AI is to simplify healthcare information retrieval by combining structured and unstructured enterprise data into a single intelligent AI assistant capable of supporting doctors, administrators, and healthcare staff.

---

## 👩‍💻 Capstone Project

**MediAssist AI – Enterprise Healthcare Agentic AI Copilot**

A Generative AI capstone project focused on building a production-inspired healthcare assistant using modern AI engineering practices, including RAG, agentic workflows, multimodal AI, MCP integration, and enterprise data retrieval.
