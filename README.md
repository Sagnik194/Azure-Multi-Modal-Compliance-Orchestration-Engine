# 🎥 Azure Multi-modal Compliance Ingestion Engine using LangGraph

An enterprise-grade **Video Compliance QA Pipeline** that automatically audits YouTube videos against regulatory and brand compliance guidelines using **Retrieval-Augmented Generation (RAG)**.

The system leverages **Azure Video Indexer** for transcript and OCR extraction, **Azure AI Search** for semantic retrieval, and **Azure OpenAI GPT-5** for intelligent compliance reasoning. **LangGraph** orchestrates the workflow, while **LangSmith** and **Azure Application Insights** provide end-to-end observability.

---

## 🚀 Features

- 🎥 YouTube video compliance auditing
- 🤖 LangGraph-based AI workflow orchestration
- 📄 Transcript & OCR extraction with Azure Video Indexer
- 🔍 RAG using Azure AI Search
- 🧠 Compliance reasoning with Azure OpenAI GPT-5
- 📊 JSON compliance reports
- 📈 LangSmith tracing & Azure Application Insights monitoring
- ⚡ FastAPI REST API

---

## 🛠 Tech Stack

- Python
- FastAPI
- LangGraph
- Azure OpenAI GPT-5
- Azure AI Search
- Azure Video Indexer
- Azure Blob Storage
- LangSmith
- Azure Application Insights
- yt-dlp

---

## 📂 Project Structure

```text
backend/
├── data/
├── scripts/
├── src/
│   ├── api/
│   ├── graph/
│   ├── services/
│   └── tests/
├── main.py
└── pyproject.toml
```

---

## ▶️ Running the Project

### Run the CLI Workflow

```bash
uv run python main.py
```

### Run the FastAPI Server

```bash
uv run uvicorn backend.src.api.server:app --reload
```

Open the API documentation:

```
http://127.0.0.1:8000/docs
```

---

## 📄 Documentation

For the complete architecture, workflow, implementation details, screenshots, and system design, please refer to:

**📘 https://drive.google.com/file/d/1bMnVwbPYfNjufbtwtgJ_sYUA3oiKuBj9/view?usp=sharing**

---

## 👨‍💻 Author

**Sagnik Sen**

AI/ML Engineer | Generative AI | Azure AI | LangGraph | FastAPI | RAG
