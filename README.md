# 🕯️ Blind Spots

Blind Spots is a calm, emotionally present conversational AI built using a Retrieval-Augmented Generation (RAG) pipeline.  
It is designed to sit with the user, reflect feelings gently, and provide grounded responses without analysis, advice, or pressure.

Rather than trying to fix problems or push conversations forward, Blind Spots focuses on comfort, presence, and clarity.

---

## 🌱 What This Project Does

- Uses Retrieval-Augmented Generation (RAG) to ground responses in provided documents
- Responds in a therapist-like, emotionally supportive tone
- Avoids advice, diagnosis, or interrogation
- Introduces itself gently at the start of a conversation
- Streams responses in real time through a simple web interface

The assistant responds with emotional presence while remaining grounded in retrieved context, rather than assumptions or external knowledge.

---

## 🧠 How It Works (High Level)

1. Documents are loaded and split into manageable chunks  
2. Chunks are embedded and stored in a Chroma vector database  
3. User input retrieves the most relevant chunks  
4. A carefully designed prompt controls tone and behavior  
5. Responses are streamed to the user using Gradio  

---

## 🛠️ Tech Stack

- Python  
- LangChain  
- ChromaDB  
- OpenAI (or compatible LLM)  
- Gradio  
- python-dotenv  

---

## 📂 Project Structure

