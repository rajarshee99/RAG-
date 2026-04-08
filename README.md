# RAG (Practice)
A modular and scalable implementation of Retrieval-Augmented Generation (RAG) that enhances LLM responses using external knowledge sources.

🚀 Overview

Traditional LLMs can hallucinate due to limited or outdated knowledge. This project solves that by:

Retrieving relevant information from a document corpus
Injecting it into the prompt
Generating grounded, context-aware responses
🧠 Architecture
User Query
     │
     ▼
Embedding Model
     │
     ▼
Vector Database (FAISS / Chroma)
     │
     ▼
Top-K Retrieval + Threshold Filtering
     │
     ▼
(Optional) Re-ranking / Hybrid Retrieval
     │
     ▼
LLM (Generator)
     │
     ▼
Final Answer
✨ Features
🔍 Semantic Search using embeddings
⚡ Fast Retrieval with FAISS / vector DB
🧩 Chunking Strategies for better context
🚫 Hallucination Control (threshold-based refusal)
🔄 Hybrid Retrieval (Optional) – BM25 + Dense
🧠 Matryoshka Representation Learning (MRL) support
📊 Multi-stage Retrieval (Coarse → Fine)
🧱 Modular design 
<img width="1536" height="1024" alt="ChatGPT Image Apr 8, 2026, 04_38_32 PM" src="https://github.com/user-attachments/assets/47694483-4950-4844-a5d5-9480f99551cb" />


