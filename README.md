# 🤖 RAG Chatbot (Retrieval-Augmented Generation)

An end-to-end AI chatbot that allows users to upload documents and ask context-aware questions using LLMs and vector search.

---

## 🚀 Live Demo
🔗 https://repository-name-rag-chatbot-cwmbqyrohht67qivy53vgz.streamlit.app/

## 💻 GitHub Repo
https://github.com/uppulasriram26-lab/Repository-name-RAG-Chatbot.git

---

## 📌 Problem Statement
Traditional chatbots fail to answer questions based on custom/private documents.  
This project solves that using **Retrieval-Augmented Generation (RAG)**.

---

## 🧠 Architecture

User Query → Embedding Model → Vector DB (ChromaDB) → Relevant Docs → LLM (OpenAI) → Answer

---

## ⚙️ Features

- 📄 Upload PDF documents
- 🔍 Semantic search using embeddings
- 🤖 AI-powered contextual answers
- 🧠 RAG pipeline using LangChain
- 💬 Interactive chat interface (Streamlit)
- ⚡ Fast retrieval using vector database

---

## 🛠️ Tech Stack

- Streamlit
- LangChain
- OpenAI API
- ChromaDB
- Python
- Sentence Transformers

---

## 📂 Project Structure
RAG-Chatbot/
│
├── frontend/
│ └── main.py
├── backend/
├── test_data/
├── requirements.txt
├── README.md

---

## 🔄 How It Works

1. User uploads document
2. Text is split into chunks
3. Embeddings are created
4. Stored in vector database (ChromaDB)
5. User query is embedded
6. Most relevant chunks retrieved
7. LLM generates final response

---

## 📈 Future Improvements

- Multi-document chat
- Chat history memory
- Authentication system
- Docker deployment
- Multi-language support

---

## 👨‍💻 Author

**Sriram Uppula**  
GitHub: https://github.com/uppulasriram26-lab/Repository-name-RAG-Chatbot.git
Architecture Diagram
User Query
   ↓
Streamlit UI
   ↓
LangChain Pipeline
   ↓
Text Embeddings (OpenAI / Sentence Transformers)
   ↓
Vector DB (ChromaDB)
   ↓
Relevant Context Retrieval
   ↓
LLM (OpenAI GPT)
   ↓
Final Answer
