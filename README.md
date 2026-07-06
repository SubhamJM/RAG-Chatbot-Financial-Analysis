# 🤖 RAG Chatbot: Corporate Policies (Apple & Google)

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Streamlit-red)](https://rag-chatbot-policies-subhamjm.streamlit.app/)

A Retrieval-Augmented Generation (RAG) chatbot designed to answer questions based on the official Code of Conduct and Corporate Policies of Apple and Google. 

This project was built to explore modern RAG architectures, document chunking, vector embeddings, and agentic workflows.

## 🚀 Live Application
**Try it out here:** [Live Streamlit App](https://rag-chatbot-policies-subhamjm.streamlit.app/)

## 🛠️ Tech Stack
* **Orchestration:** LangChain & LangGraph
* **Vector Database:** ChromaDB
* **Embeddings:** `all-MiniLM-L6-v2` (Sentence Transformers)
* **LLM:** Google Gemini 3.1 Flash Lite
* **Frontend/UI:** Streamlit

## ✨ Features
* **Context-Aware Responses:** Answers are grounded purely in the provided corporate policy documents, reducing LLM hallucination.
* **Semantic Search:** Uses dense vector embeddings to retrieve the most relevant sections of the policies based on user queries.
* **Interactive UI:** A clean, easy-to-use chat interface built with Streamlit.

## 💡 Example Questions to Try
* *"What is Google's stance on conflicts of interest?"*
* *"How does Apple handle third-party vendor confidentiality?"*
* *"What are the rules regarding accepting gifts at Google?"*
