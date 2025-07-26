# 🤖 PDF Question Answering Chatbot using OpenAI and LangChain

This is a **Streamlit-based AI chatbot** that allows users to upload a **PDF document** and ask questions based on its content. The app uses **OpenAI's GPT model**, **LangChain**, and **FAISS** to understand and respond intelligently.

---

## 📌 Features

- 📄 Upload PDF files via a user-friendly interface
- 🔍 Extracts and splits text into manageable chunks
- 🧠 Generates embeddings using OpenAI
- 📚 Stores embeddings in FAISS for similarity search
- 💬 Asks questions and receives answers from GPT-3.5-turbo

---

## 🛠️ Tech Stack

| Technology     | Purpose                               |
|----------------|----------------------------------------|
| Python         | Programming language                   |
| Streamlit      | Web UI framework                       |
| PyPDF2         | PDF text extraction                    |
| LangChain      | LLM orchestration                      |
| FAISS          | Vector similarity search               |
| OpenAI         | Embedding + GPT language model         |

---

## 📁 Project Structure
│
├── chatbot.py # Main application code
└── README.md # Project documentation (this file)


---

## 🔐 Prerequisites

- Python 3.8 or later
- OpenAI API Key from [https://platform.openai.com/](https://platform.openai.com/)

---

## 🚀 Getting Started


▶️ Run the App
streamlit run app.py

