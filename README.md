# 📄 PDF Q&A with Multi-Modal Retrieval (Gemini-powered)

This project allows you to **upload a PDF** into a **Jupyter Notebook** and then **ask natural language questions** about its contents — including **text, tables, and images** — using **Google Gemini** (free model).  

It combines:
- **PDF parsing** (text, tables, images)
- **Summarization** of each extracted element using Gemini
- **Vector-based semantic search**
- **Multi-modal question answering** (answers using both text and images)

---

## ✨ Features
- 📜 Extracts **text, tables, and images** from PDFs
- 🧠 Summarizes content with **Gemini**
- 🔍 Stores summaries in a **vector database** for fast retrieval
- ❓ Answer questions with **context-aware multi-modal responses**
- ⚡ Works entirely inside **Google Colab** or local **Jupyter Notebook**

---

## 📂 Project Structure
├── Langchain Multimodal Rag.ipynb # Main notebook with complete code & instructions

├── README.md # Project documentation

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/Prathamesh-Palatshaha/Research-Paper-Summarizer
```
## ⚠️ Important Note
> If you find any API key left in the code, **you won’t be able to use it** — I have already removed all working keys from the source.  
> Please **create and use your own API key** as described below.
> 
## 🔑 API Key Setup
 - This project uses Google Gemini. You need a free API key.

- Go to Google AI Studio

- Create a new API key

- In Colab or Jupyter, set your API key:
```bash
import os
os.environ["GOOGLE_API_KEY"] = "your_api_key_here"
```
## 🧩 Workflow
- Upload a PDF
- Extract text, tables, and images
- Summarize each element with Gemini
- Store summaries in a vector database
- Ask questions — answers are generated with multi-modal context
