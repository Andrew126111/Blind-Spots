# Blind-Spots
a RAG-based AI that explains cognitive biases, decision-making, and emotion using grounded research documents

# RAG Chatbot

This project is a Retrieval-Augmented Generation (RAG) chatbot that answers questions using information from custom documents rather than relying only on a language model’s general knowledge.

The chatbot retrieves relevant content from provided documents and uses that information as context to generate more accurate, grounded, and informative responses.

---

## 💡 Why I Built This Project

I built this project because I enjoy working with AI and wanted to learn more about machine learning, chatbot systems, and how tools like LangChain and Retrieval-Augmented Generation (RAG) work in practice.

I was also motivated by personal experience. During stressful periods such as exam season, it can be helpful to understand *why* certain feelings or reactions occur from a more scientific or informational perspective. While friends can offer comfort and reassurance, this chatbot is designed to provide structured, knowledge-based explanations using reliable information.

---

## 🚀 Features
- Retrieval-Augmented Generation (RAG) pipeline
- Uses custom documents (PDFs / Markdown files)
- Semantic search with embeddings
- Context-aware responses
- Modular and easy to extend

---

## 🧠 How It Works
1. Documents are loaded and split into smaller chunks  
2. Each chunk is converted into vector embeddings  
3. Embeddings are stored in a vector database  
4. When a user asks a question:
   - Relevant chunks are retrieved based on similarity
   - The language model generates a response using that context

---

## 📁 Project Structure
│── data/ # PDF or Markdown knowledge sources
│── embeddings/ # Vector database files
│── app.py # Main chatbot logic
│── requirements.txt
│── README.md

## 🛠️ Technologies Used
- Python
- OpenAI API
- LangChain
- Vector database (e.g., ChromaDB)
