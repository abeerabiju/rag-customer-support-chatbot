
# RAG Customer Support Chatbot

A team project exploring Retrieval-Augmented Generation (RAG) for customer support using n8n, Ollama, Mistral, and Pinecone.

## Overview

Developed a customer support chatbot concept for Happy Furnitures GmbH. The system retrieves relevant information from company documents before generating answers to customer questions.

## Tech Stack

- **Workflow automation:** n8n
- **LLM:** Mistral via Ollama
- **Vector database:** Pinecone
- **Embeddings:** nomic-embed-text
- **Document source:** Google Drive

## How It Works

1. Retrieve and process knowledge documents from Google Drive.
2. Split documents into text chunks and generate embeddings.
3. Store embeddings in Pinecone.
4. Retrieve relevant context for a customer question.
5. Generate a context-based response using Mistral through Ollama.

## Key Learnings

- Building document ingestion and retrieval workflows.
- Integrating LLMs with vector databases.
- Troubleshooting embedding compatibility and retrieval issues.


