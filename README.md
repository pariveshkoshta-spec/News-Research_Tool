# News Research Tool

This project is a GenAI-based news research and question-answering system developed to extract
actionable insights from financial and stock market news articles using semantic search and
Large Language Models.

The system implements an end-to-end Retrieval-Augmented Generation (RAG) pipeline that
transforms unstructured news content into a searchable knowledge base and generates
context-aware answers grounded in retrieved sources.

## Project Objective

To design and implement a scalable RAG-based system that enables efficient research across
multiple financial news articles with accurate, source-backed responses.

## What Was Implemented

- Designed and implemented an end-to-end Retrieval-Augmented Generation (RAG) pipeline
- Loaded and processed unstructured financial news articles from multiple URLs
- Cleaned, segmented, and prepared article text for embedding generation
- Generated dense semantic embeddings using OpenAI Embeddings
- Indexed embeddings using FAISS for fast similarity-based retrieval
- Implemented semantic search to retrieve the most relevant context per query
- Integrated an LLM to generate grounded answers from retrieved content
- Enabled source attribution to ensure transparency and reliability of responses
- Built an interactive research interface for querying processed articles

## System Output Preview

The image below shows the working interface of the News Research Tool, including URL ingestion,
semantic processing, and question-answering over financial news articles:

![News Research Tool Interface Preview](newsresearchtool.png)

## Key Concepts Demonstrated

- Retrieval-Augmented Generation (RAG)
- Vector embeddings and semantic similarity search
- FAISS-based indexing for efficient retrieval
- LLM grounding using external knowledge sources
- Practical application of LangChain components

## Tech Stack Used

- Python
- LangChain
- OpenAI API
- FAISS
- Streamlit

## Project Artifacts

- `main.py` – Core implementation of the RAG pipeline and query flow
- `faiss_store_openai.pkl` – Persisted FAISS vector index for semantic retrieval
- `newsresearchtool.jpg` – Visual preview of the application interface
- `requirements.txt` – Dependency specifications

## Author

**Developed by:** Parivesh Koshta  

This project was independently implemented to demonstrate applied expertise in Generative AI,
LLM-powered systems, and retrieval-based architectures for real-world financial research.
