# InsightDoc AI – Multimodal Document Intelligence System

## Overview
InsightDoc AI is a multimodal document intelligence system designed to extract, analyze, and query information from complex documents such as PDFs containing text, tables, and images.

## Features
- Multimodal document processing (text, images, tables)
- OCR integration for scanned documents
- Retrieval-Augmented Generation (RAG) pipeline
- Semantic search using vector embeddings
- Context-aware question answering
- Scalable FastAPI backend

## Tech Stack
Python, FastAPI, FAISS, Tesseract OCR, OpenAI/Gemini APIs

## Architecture
Document Upload → OCR → Chunking → Embedding → Vector Storage → Retrieval → LLM Response

## Future Work
- Real-time streaming responses
- UI dashboard
- Multi-document comparison
