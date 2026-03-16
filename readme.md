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
├── rag_starter_code.ipynb
│
├── data/
   └── sample.pdf
```

## Installation

Clone the repository:
```bash
git clone https://github.com/your-username/pdf-rag-workshop.git
cd pdf-rag-workshop
```

Create a virtual environment:
```bash
python -m venv .venv
source .venv/bin/activate
```

Install dependencies:
```bash
pip install -r requirements.txt
Environment Variables
```

Create a .env file based on .env.example:
```bash
GROQ_API_KEY=your_groq_api_key_here
```

Run in Jupyter / Colab
Open the notebook:
```bash
jupyter notebook notebooks/groq_rag_starter_colab.ipynb
```
Or upload the notebook to Google Colab and run it there.
