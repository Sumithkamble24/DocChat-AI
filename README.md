# DocChat-AI

DocChat-AI is a GenAI-based Document Question Answering application built using
Retrieval-Augmented Generation (RAG).  
It allows users to ask questions and receive answers based on the content of uploaded documents.

---

## 🚀 Features
- Document-based question answering using LLMs
- Semantic search with vector embeddings
- Context-aware responses grounded in document data
- Simple web-based interface
- End-to-end GenAI application workflow

---

## 🧠 How It Works (RAG Pipeline)
1. Document text is extracted and split into chunks  
2. Embeddings are generated for each chunk  
3. Chunks are stored in a vector store  
4. User queries are embedded and matched with relevant chunks  
5. Retrieved context is passed to an LLM to generate accurate answers  

---

## 🛠️ Tech Stack
- **Backend:** Node.js / Python
- **LLM:** OpenAI API or open-source LLM
- **Vector Store:** FAISS
- **Frontend:** HTML, CSS
- **Deployment:** Free-tier cloud platform

---

## 📂 Project Structure
