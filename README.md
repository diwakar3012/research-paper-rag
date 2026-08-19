Research Paper RAG

A hands-on implementation of a Retrieval-Augmented Generation (RAG) pipeline for querying research papers.

This project was developed in Google Colab to understand how document retrieval, vector search, reranking, and LLM generation work together in an end-to-end RAG workflow.

🔎 Pipeline
Research Papers
      ↓
PDF Text Extraction
      ↓
Text Chunking
      ↓
Bi-Encoder Embeddings
      ↓
Weaviate
      ↓
Hybrid Retrieval
(Vector Search + BM25)
      ↓
Cross-Encoder Reranking
      ↓
Context Augmentation
      ↓
LLM Generation
      ↓
Final Answer
🛠️ Technologies
Python
Google Colab
PyPDF
Sentence Transformers
Weaviate
BM25
Cross-Encoder
Groq
Large Language Models (LLMs)
🧩 What I Explored
Extracting and chunking text from research papers
Generating document embeddings using a bi-encoder
Storing and retrieving documents using Weaviate
Combining vector search and BM25 using hybrid retrieval
Reranking retrieved documents using a cross-encoder
Building context for LLM generation
Generating grounded responses from retrieved context
📓 Notebook

The complete implementation is available in:

Research_Paper_RAG.ipynb

The notebook contains the complete experimentation and implementation of the RAG pipeline.

🚀 Running the Project

The notebook was developed and tested in Google Colab.

Open Research_Paper_RAG.ipynb in Google Colab and execute the cells sequentially.

You will need API credentials for the external services used in the notebook. Do not commit API keys or other secrets to the repository.

📌 Project Status

This is a learning and experimentation project focused on understanding the components of a RAG system and how they work together.

Future improvements may include retrieval evaluation, parameter experimentation, API integration, and deployment.

Author: Diwakar S