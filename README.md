# 📄 LangChain Q&A PDF Chatbot

A lightweight chatbot app built with **LangChain**, **Gemini Pro**, and **Chroma Vector DB** that allows users to upload a PDF and ask questions based on its contents in real-time using a **RAG (Retrieval-Augmented Generation)** pipeline.

## 🚀 Features

- Upload and interact with any PDF file
- Context-aware question answering using Gemini Pro
- Document chunking and vector storage via Chroma
- Simple and fast UI using Streamlit

## 🧠 Tech Stack

- **LangChain** – RAG pipeline management  
- **Google Gemini Pro** – LLM for answering questions  
- **Chroma Vector DB** – Storing & querying text embeddings  
- **Streamlit** – User interface  
- **PyPDF2** – PDF parsing    

## 🛠️ Setup Instructions

1. **Clone the repository**
```bash
git clone https://github.com/harshal-nelge/langchain_qanda_chatbot.git
cd langchain_qanda_chatbot
pip install -r requirements.txt

// Create .env file and include your GEMINI API KEY
GEMINI_API_KEY=your_api_key_here

streamlit run app.py



