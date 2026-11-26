# Ask Your Documents — Full-Stack AI RAG Assistant

A full-stack Retrieval-Augmented Generation (RAG) web application built with **React**, **TypeScript**, **FastAPI**, **LangChain**, and **FAISS** that allows users to upload PDF documents and query them with grounded, source-cited answers.

## Tech Stack
- **Frontend:** React 18, TypeScript, Vite, Tailwind CSS
- **Backend:** Python, FastAPI, LangChain, FAISS Vector Store, Server-Sent Events (SSE)

## Key Features
- **PDF Ingestion & Chunking:** Extracts text from uploaded PDFs and splits content into overlapping chunks for accurate semantic retrieval.
- **Session-Isolated Vector Search:** Uses FAISS in-memory vector indexing per session for fast similarity search without requiring user login.
- **Real-Time Streaming:** Streams LLM responses token-by-token via Server-Sent Events (SSE) with source citations.
