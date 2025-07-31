# 🤖 Multi-Actor AI Chatbot using LangChain, LangGraph, and HuggingFace

This repository contains a Jupyter notebook implementation of a **multi-agent chatbot system**, built with modern LLM tools like LangChain, LangGraph, ChromaDB, and HuggingFace Transformers.

## 🚀 Features

- 🔗 Loads and indexes content from blogs or websites
- 🔍 Splits documents into chunks for semantic search
- 🧠 Embeds and stores text using HuggingFace + ChromaDB
- 🤝 Enables multi-actor dialogue agents
- 🧾 Uses LangGraph to manage complex agent logic flows
- 🗃️ Stores data persistently with AstraDB (Cassandra backend)

## 🧱 Stack

- Python
- LangChain
- LangGraph
- ChromaDB
- HuggingFace Embeddings
- Astra DB
- tiktoken, langchainhub, cassio

## 📦 Installation

```bash
pip install langchain langgraph langchain_community langchain-groq \
            langchainhub chromadb tiktoken huggingface_hub \
            astrapy cassio
📁 Files
Multi_actor_chabot.ipynb: Main notebook with full pipeline

requirements.txt: (Optional) Dependencies list (can be generated)

README.md: Project overview

📘 Indexed Resources
This chatbot loads and indexes content from:

Prompt Engineering for LLMs

Agent Design

Adversarial Attacks on LLMs

🛠️ Setup
Clone the repo

Set your Astra DB credentials:

python
Copy
Edit
ASTRA_DB_APPLICATION_TOKEN = "your_token"
ASTRA_DB_ID = "your_db_id"
Run all notebook cells

🙋‍♂️ Author
Built by Aryansh Gupta as part of personal LLM exploration projects.
