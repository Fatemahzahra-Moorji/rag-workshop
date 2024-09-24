# rag-workshop
Comapany Documents Chatbot with RAG Pipeline

Project Overview

This project involves building a chatbot capable of answering questions based on internal company documents. The chatbot uses Retrieval-Augmented Generation (RAG) to enhance its responses by retrieving and processing relevant information from the company’s knowledge base.

Key Features
- Natural Language Processing: Leverages Large Language Models (LLMs) to provide intelligent, human-like responses.
- Document Embedding: Converts internal documents into vector embeddings and stores them in Pinecone for fast retrieval.
- Dynamic Knowledge Base: Performs real-time querying over the stored data to ensure responses are always based on the most relevant company documents.

How It Works
- Document Processing:
  - Each company document is processed and converted into vector embeddings, making it easier for the system to retrieve key information quickly.
- Embedding Storage:
  - The embeddings are stored in Pinecone, a vector database designed for fast, scalable storage and retrieval of document embeddings.
- Retrieval-Augmented Generation (RAG):
  - When a user asks a question, the system retrieves relevant document embeddings from Pinecone. The LLM then uses this data to generate a detailed, context-aware response.
