🕯️ Blind Spots

Blind Spots is a calm, emotionally present conversational AI built using a Retrieval-Augmented Generation (RAG) pipeline.
It is designed to sit with the user, reflect feelings gently, and provide grounded responses without analysis, advice, or pressure.

Rather than trying to fix problems or push conversation forward, Blind Spots focuses on comfort, presence, and clarity.

🌱 What This Project Does

Uses RAG (Retrieval-Augmented Generation) to ground responses in provided documents

Responds in a therapist-like, emotionally supportive tone

Avoids advice, diagnosis, or interrogation

Introduces itself gently at the start of a conversation

Streams responses in real time via a simple web interface

The assistant only responds based on retrieved context and emotional presence — not assumptions or external knowledge.

🧠 How It Works (High Level)

Documents are loaded and split into chunks

Chunks are embedded and stored in a Chroma vector database

User input retrieves the most relevant chunks

A carefully designed prompt guides the model’s tone and behavior

Responses are streamed to the user using Gradio

🛠️ Tech Stack

Python

LangChain

ChromaDB

OpenAI / compatible LLM

Gradio

dotenv

📂 Project Structure
.
├── data/               # Source documents
├── chroma_db/          # Vector database
├── create_database.py  # Builds the vector store
├── chatbot.py          # Chat interface + prompt logic
├── .env                # Environment variables (not committed)
├── .gitignore
└── README.md

🚧 Current Status

This is an early-stage project built as a learning experience.
The focus so far has been on:

Prompt design

Emotional tone

RAG fundamentals

System behavior boundaries

Future improvements may include:

Better context handling

Local/offline models

Improved UI

More refined emotional responses

⚠️ Notes

This project is not a replacement for therapy or mental health care

It does not give advice, diagnoses, or treatment

It is intended as a supportive, reflective tool only

✨ Why This Exists

This project explores how AI can feel less mechanical and more present, without pretending to be human or offering guidance it shouldn’t.

Sometimes, clarity starts with being heard.
