# MedRAG-AI-Powered-Hospital-Document-Intelligence-Platform
Hospital-grade AI platform for querying medical PDFs using Retrieval-Augmented Generation (RAG) with source citations, built using FastAPI, LangChain, Streamlit, and local LLMs.


# 🏥 MedRAG – AI-Powered Hospital Document Intelligence Platform

MedRAG is an end-to-end **hospital-grade Retrieval-Augmented Generation (RAG)** system designed to extract actionable insights from medical documents such as **discharge summaries, radiology reports, insurance claims, and research papers**.
The platform delivers **evidence-based answers with source citations**, ensuring explainability and clinical trust.

---

## 🚀 Key Features

* 🧠 **RAG-based Medical QA** using local LLMs (LLaMA 3 via Ollama)
* 📄 Query multiple medical PDF documents
* 📑 **Source citations** (document name + page number)
* 📤 **Real-time PDF upload and re-indexing**
* 🩺 **Hospital-style Streamlit dashboard**
* 📊 Clinical audit trail for previous queries
* 🔐 Privacy-preserving, offline-capable architecture

---

## 🏗️ System Architecture

```
Streamlit (Frontend)
        ↓
FastAPI (Backend API)
        ↓
RAG Engine (LangChain)
        ↓
Vector Database (Chroma / FAISS)
        ↓
Local LLM (LLaMA 3 via Ollama)
```

---

## 🧰 Tech Stack

* Python
* FastAPI
* LangChain
* Ollama (LLaMA 3)
* HuggingFace Embeddings
* Chroma / FAISS
* Streamlit

---

## ⚙️ Installation & Setup

```bash
git clone https://github.com/your-username/MedRAG.git
cd MedRAG
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
```

---

## ▶️ Run Backend (FastAPI)

```bash
cd backend
uvicorn main:app --reload
```

API Documentation:
👉 [http://127.0.0.1:8000/docs](http://127.0.0.1:8000/docs)

---

## ▶️ Run Frontend (Streamlit)

```bash
cd frontend
streamlit run medrag_dashboard.py
```

Dashboard:
👉 [http://localhost:8501](http://localhost:8501)

---

## 📤 Upload Medical PDFs

* Upload new patient or hospital documents directly from the dashboard
* Files are automatically indexed and immediately available for querying

---

## 🧠 Sample Questions

* What treatment was given to the patient?
* What abnormalities were found in the radiology report?
* What medications were prescribed at discharge?
* What is the insurance claim amount?

---

## 📌 Use Cases

* Clinical decision support
* Medical document intelligence
* Healthcare AI research
* Hospital record analysis

---

## 📜 License

This project is intended for educational and research purposes.

---

## ✨ Author

**Bhavya Das**
 Data Science | Healthcare AI

---

 Project Summary 

> Hospital-grade RAG system delivering explainable, citation-backed insights from medical documents using local LLMs and FastAPI.

