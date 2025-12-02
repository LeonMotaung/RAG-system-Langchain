# Building a RAG System for Web Data with Llama 3.1-405B

**Author:** Leon Motaung

---

## Overview

This project demonstrates a **Retrieval-Augmented Generation (RAG)** system using LangChain and **Meta Llama 3.1-405B** on **IBM watsonx.ai**. The system fetches content from web pages, converts it into vector embeddings, and allows context-aware question answering using a large language model (LLM).

---

## Technologies Used

Python, LangChain, Meta Llama 3.1-405B, IBM watsonx.ai, Vector Databases, Web Scraping (BeautifulSoup, Requests), Pandas, NumPy, Retrieval-Augmented Generation (RAG), Prompt Engineering, JSON, API Integration

---

## Project Structure

- **Web Data Extraction** – Fetch and parse web page content.  
- **Vector Embeddings** – Convert text to embeddings for retrieval.  
- **Vector Store** – Store and query embeddings efficiently.  
- **Retriever** – Search vector database to find relevant context.  
- **LLM Query** – Use Llama 3.1-405B to answer questions with retrieved context.

---

## Demo

Example usage:

```python
from langchain.chains import RetrievalQA

# Fetch and embed content from web pages
# (example code for demonstration purposes)
response = chain.invoke("Tell me about IBM Cloud")
print(response)
