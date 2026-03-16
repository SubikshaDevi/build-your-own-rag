# Build your own RAG Workshop

Build your own AI system that answers questions from PDFs using Retrieval Augmented Generation (RAG).

This repository contains starter code and a workshop notebook for building a simple PDF question-answering pipeline using:

- Python
- PyPDF
- Sentence Transformers
- ChromaDB
- Groq API

## What You’ll Build

In this workshop, you will learn how to:

1. Load a PDF
2. Extract text
3. Split the text into chunks
4. Generate embeddings
5. Store vectors in a vector database
6. Retrieve relevant chunks
7. Ask an LLM to answer using that context

## RAG Pipeline

PDF → Text Extraction → Chunking → Embeddings → Vector Database → Retrieval → LLM → Answer

## Repository Structure

```bash
build-your-own-rag/
│
├── README.md
├── requirements.txt
├── .gitignore
├── .env.example
│
├── notebooks/
│   └── groq_rag_starter_colab.ipynb
│
├── data/
   └── sample.pdf
