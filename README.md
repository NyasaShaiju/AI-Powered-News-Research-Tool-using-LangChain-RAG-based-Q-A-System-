# AI-Powered-News-Research-Tool-using-LangChain-RAG-based-Q-A-System-
Overview

This project is an AI-powered news research assistant that allows users to input multiple news article URLs and ask questions based on their content. The system processes the articles and generates context-aware answers with source references using a Retrieval-Augmented Generation (RAG) pipeline.


Features
Extracts and processes content from multiple news URLs
Uses LLMs to generate intelligent answers
Semantic search using vector embeddings
Provides source references for transparency
Fast retrieval using FAISS vector database
Simple UI built with Streamlit


Architecture
User Input (URLs + Question)
        ↓
Load Articles (URL Loader)
        ↓
Text Chunking
        ↓
Embeddings (OpenAI)
        ↓
Vector Storage (FAISS)
        ↓
Similarity Search (Retrieval)
        ↓
LLM (Answer Generation)
        ↓
Final Answer + Sources


Tech Stack
LangChain – Orchestrates the RAG pipeline
OpenAI API – Embeddings & LLM
FAISS – Vector database for similarity search
Streamlit – Frontend UI
Python – Backend logic


Usage
Enter one or more news article URLs
Click Process URLs
Ask a question related to the articles
View:
AI-generated answer
Source references


Example

Input:

URLs of financial news articles

Question:

What is the impact of inflation on stock markets?

Output:

Context-aware answer
Based on provided articles
Includes source links


Key Concepts Used: 
Retrieval-Augmented Generation (RAG)
Natural Language Processing (NLP)
Text Embeddings
Vector Search (FAISS)
LLM-based Question Answering
onstrates how to build a real-world AI application using LangChain and RAG, enabling efficient analysis and querying of unstructured news data.
