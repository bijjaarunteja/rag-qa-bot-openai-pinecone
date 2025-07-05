# rag-qa-bot-openai-pinecone
Retrieval-Augmented Generation QA Bot using OpenAI API and Pinecone
# Retrieval-Augmented Generation (RAG) QA Bot with OpenAI & Pinecone

This project is a Question Answering (QA) system for businesses using the Retrieval-Augmented Generation (RAG) architecture.

## 🚀 Features
- PDF document ingestion and chunking
- Embedding using OpenAI's `text-embedding-ada-002`
- Vector storage and search using Pinecone
- Context-aware GPT-3.5 Turbo responses based on uploaded business documents

## 🧠 Technologies
- OpenAI API (GPT-3.5 Turbo + Embeddings)
- Pinecone vector database
- Langchain (optional)
- Python + Google Colab

## 📄 How It Works
1. PDF is uploaded and text is chunked
2. Chunks are embedded using OpenAI embeddings
3. Vectors are stored in Pinecone
4. User asks a question → relevant chunks retrieved → passed to GPT model for answer

## ✅ Requirements
- OpenAI API key
- Pinecone API key and index
- Google Colab or Python environment

## 📝 Author
Built by [Your Name] as part of an AI/ML project submission.
