# Enterprise AI Copilot

AI document assistant built with FastAPI and Retrieval Augmented Generation (RAG).

## Features

- Upload documents (PDF, TXT, CSV)
- Vector search using FAISS
- Retrieval Augmented Generation (RAG)
- Chat mode
- Multi-LLM support (Gemini, Claude, OpenAI, Ollama)
- Persistent vector database

## Tech Stack

- FastAPI
- FAISS
- Sentence Transformers
- Gemini API
- Python

## Run Locally

Clone the repo

git clone https://github.com/YOUR_USERNAME/enterprise-ai-copilot.git

Install dependencies

pip install -r requirements.txt

Run server

uvicorn app.main:app --reload