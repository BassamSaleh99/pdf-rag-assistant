# 📚 pdf-rag-assistant

An AI-powered Retrieval-Augmented Generation (RAG) system that ingests PDF documents, embeds them into a vector database (Qdrant), and allows users to query and receive contextually accurate answers from their uploaded files.
Built with Streamlit, Inngest, Qdrant, and OpenAI embeddings, this project demonstrates a production-ready RAG pipeline — from PDF ingestion to semantic retrieval and intelligent question answering.

## 🚀 Project Overview

The RAG PDF Intelligence app automates the ingestion and semantic understanding of PDF files.
It combines chunk-based document embedding, vector similarity search, and LLM reasoning to deliver precise answers grounded in the uploaded content.

#### The workflow includes:

🧾 PDF Upload & Processing – PDFs are chunked, embedded, and stored in Qdrant.

🔍 Vector Search – Similar document chunks are retrieved using semantic search.

🧠 LLM Reasoning – The system generates an answer using only relevant retrieved text.

⚙️ Event-driven Orchestration – All ingestion and query processes are managed through Inngest event workflows.

## 🛠 Tech Stack

🧠 OpenAI Embeddings / LangChain – Text embeddings & retrieval logic

💾 Qdrant – Vector database for semantic search

⚙️ Inngest – Event-driven orchestration for ingestion & querying

🌐 Streamlit – Intuitive frontend interface for users

📦 Python – Backend with async event functions and Pydantic models