# GenAI-Chatbot-PDF-RAG
Ask questions directly from uploaded PDFs using LLMs and RAG

# 🤖 GenAI Chatbot | PDF-RAG (Retrieval-Augmented Generation)

A powerful GenAI chatbot that reads PDF files, intelligently chunks the content, embeds it using OpenAI, stores it in a vector database, and lets users ask natural language questions about the document — all built using RAG (Retrieval-Augmented Generation) architecture.

---

## 📌 Features

- 📄 Upload and process one or more PDF files
- 🧠 Uses OpenAI Embeddings to convert chunks into vectors
- 🔎 Fast retrieval using FAISS or ChromaDB
- 💬 Ask questions and get accurate answers based on your PDF
- ⚙️ Chunk size and overlap are configurable
- 🖥️ Streamlit app for user-friendly interaction

---

## ⚙️ Tech Stack

| Layer        | Tools / Libraries                          |
|--------------|--------------------------------------------|
| LLMs         | OpenAI (`text-embedding-ada-002`)          |
| Embedding    | LangChain + OpenAI                         |
| Vector DB    | FAISS / ChromaDB                           |
| Backend      | Python, LangChain                          |
| UI           | Streamlit                                  |
| File Support | PDF via PyPDF2 / pdfminer                  |
| Deployment   | Local (Docker-ready)                       |

---

## 📁 Project Structure
