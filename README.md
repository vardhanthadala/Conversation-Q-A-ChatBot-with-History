# Conversational Q&A Chatbot with LangChain & Groq

This project demonstrates how to build a **Conversational Q&A Chatbot** that can answer questions based on external documents and remember chat history.  
It combines **LLMs (Llama3 via Groq API)**, **retrieval from vector stores**, and **document loading from the web**.  

---

## 🚀 Features
- Uses **Groq API** with Llama3-8B model for chat responses.  
- Integrates **HuggingFace embeddings** (`all-MiniLM-L6-v2`).  
- Stores vectors in **ChromaDB** for efficient retrieval.  
- Loads and parses blog content using **BeautifulSoup (bs4)**.  
- Supports **chat history** for contextual conversation.  
- Built inside a **Jupyter Notebook** for easy experimentation.  

---

## 📂 Tech Stack
- **Python**
- **LangChain**
- **Groq API** (Llama3)
- **HuggingFace Transformers**
- **ChromaDB**
- **BeautifulSoup4**
- **Jupyter Notebook**

---

## ⚙️ Installation

1. Clone the repository:
   ```bash
   git clone <your-repo-link>
   cd <your-repo-name>
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
    ```
3. Set up your API keys in a .env file:
    ```bash
    GROQ_API_KEY=your_groq_api_key
    HF_TOKEN=your_huggingface_token
    ```

 ## 🎯 Use Case
This chatbot is useful for:
  - Summarizing and querying blog posts or documentation.
  - Building Retrieval-Augmented Generation (RAG) systems.
  - Demonstrating LLM + Vectorstore + Retriever workflow.
