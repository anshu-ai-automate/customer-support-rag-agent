# Customer Support AI Agent — Edge Realty

An AI-powered customer support agent built for a fictional real estate company called Edge Realty. The agent answers customer queries using a RAG pipeline connected to a knowledge base.

## What it does
- Accepts customer questions via chat
- Searches the knowledge base using vector similarity
- Returns accurate, context-aware answers

## Tech Stack
- n8n (workflow automation)
- Pinecone (vector database)
- Ollama — nomic-embed-text (embeddings)
- Groq — LLaMA 3.2 (LLM)
- Google Drive (knowledge base storage)
- Gmail (customer feedback)

## Setup
1. Import the JSON file into your n8n instance
2. Connect your own credentials (Pinecone, Groq, Ollama, Google Drive)
3. Upload the included knowledge base PDF to Google Drive
4. Update the Google Drive file ID in the workflow
5. Activate the workflow

## Note
All credentials and file IDs have been removed from the workflow JSON. Add your own before running.
