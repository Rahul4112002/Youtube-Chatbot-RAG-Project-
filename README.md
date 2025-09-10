# 🎥 YouTube Chatbot using LangChain (RAG System)

Chat with any YouTube video! This project implements **Retrieval Augmented Generation (RAG)** using **LangChain** to answer questions from YouTube transcripts.

---

## 📌 Features

* Extract transcript from any YouTube video (supports multiple languages).
* Split transcripts into manageable chunks.
* Generate embeddings and store them in a **vector database (FAISS)**.
* Retrieve the most relevant transcript sections using **semantic search**.
* Answer user queries using **OpenAI LLMs** with transcript context.
* Prevents hallucination by restricting answers to transcript content.

---

## 🏗️ RAG Workflow

1. **Transcript Loading** → Extract transcript from YouTube.
2. **Text Splitting** → Break into smaller chunks.
3. **Embeddings** → Convert chunks into embeddings.
4. **Vector Store** → Store embeddings in FAISS.
5. **Retriever** → Retrieve top-k relevant chunks.
6. **Prompt Augmentation** → Merge retrieved chunks with user query.
7. **Generation** → LLM generates final answer.

---



### Requirements

* Python 3.9+
* [Google API Key]
* Required Python packages 

  ```txt
  langchain
  google-genai
  faiss-cpu
  youtube-transcript-api
  tiktoken
  ```

---

## 🚀 Usage

### 1️⃣ Run in Google Colab

Open the notebook in `youtube_rag.ipynb` and run step by step.


## 📊 Applications

* 📚 Education → Summarize long lectures.
* 🎙️ Podcasts → Extract insights.
* 👩‍💻 Developers → Quickly find relevant sections.
* 📰 Content creators → Repurpose video content into blogs or posts.

---

## 🔮 Future Improvements

* Build a **Streamlit web app**.
* Create a **Chrome extension** for direct YouTube integration.
* Support for **multi-video knowledge base**.
* Add **speech-to-text** for videos without transcripts.

---


