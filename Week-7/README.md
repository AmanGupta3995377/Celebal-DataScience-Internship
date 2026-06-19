# Week 7 - Document Question Answering System using RAG

## Overview

This project implements a Retrieval-Augmented Generation (RAG) based document question answering system. The system processes a PDF document, converts the text into vector embeddings, stores them in a FAISS vector database, and retrieves relevant document chunks based on user queries.

## Dataset

Cyber Security Notes PDF (93 Pages)

## Technologies Used

* Python
* LangChain
* FAISS
* Sentence Transformers
* Hugging Face Transformers
* Google Colab

## Workflow

1. Document Ingestion
2. Text Extraction
3. Text Chunking
4. Embedding Generation
5. FAISS Vector Database Creation
6. Query Processing
7. Context Retrieval

## System Configuration

| Component           | Value            |
| ------------------- | ---------------- |
| Chunk Size          | 500              |
| Chunk Overlap       | 50               |
| Embedding Model     | all-MiniLM-L6-v2 |
| Embedding Dimension | 384              |
| Vector Store        | FAISS            |
| Top-K Retrieval     | 3                |

## Results

* Successfully loaded and processed a 93-page PDF document.
* Generated 148 text chunks from the extracted content.
* Created vector embeddings using the all-MiniLM-L6-v2 model.
* Stored embeddings in a FAISS vector database for efficient similarity search.
* Retrieved contextually relevant document chunks for cybersecurity-related queries.
* Validated retrieval performance using multiple sample questions.

## Conclusion

This project demonstrates the implementation of a basic RAG pipeline for document retrieval and question answering. It provided practical experience with embeddings, vector databases, semantic search, and retrieval-based AI systems.
