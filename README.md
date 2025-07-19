
# Skillathon
# Build Your Own AI Clone 🤖

# 🤖 Build Your Own AI Chatbot (Hugging Face RAG)

This project demonstrates how to build your own **AI-powered RAG (Retrieval-Augmented Generation) chatbot** using Hugging Face models, FAISS vector store, and PDF document ingestion — **without requiring an OpenAI API key**.



 ## Notebook Access

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/<your-username>/<your-repo-name>/blob/main/my_own_ai_clone.ipynb)


 ## Features

 -RAG (Retrieval-Augmented Generation)** pipeline
 - PDF ingestion** with automatic text extraction
 - FAISS-based vector database** for fast similarity search
 - Sentence-transformers** for embeddings
 -Context-aware responses** using Hugging Face LLM
 - Prompt Engineering** for relevant and grounded replies
 -No OpenAI API required** – uses Hugging Face only



##  Requirements

- Python 3.8+
- Google Colab / Jupyter Notebook
- Hugging Face account + token



##  Installation

In Colab or your local environment, install the required libraries:

`bash
!pip install sentence-transformers
!pip install faiss-cpu
!pip install transformers
!pip install PyMuPDF


## Hugging Face Token Setup

Create a Hugging Face account at huggingface.co

Generate an access token: Settings > Access Tokens

Add your token in the notebook:

from huggingface_hub import login
login(token="your_hf_token_here")

## Example Queries
query = "What is FAISS?"
# 🤖 Facebook AI Research

query = "What is LangChain used for?"
# 🤖 building applications using language models
























