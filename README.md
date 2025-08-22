# 🦁 Puneet GenAI SQL Chatbot

A **Generative AI-powered SQL chatbot** built with **Streamlit**, **LangChain**, and **Groq’s Llama3 model** that enables users to query **SQLite** and **MySQL** databases using plain English.

The app intelligently converts your natural language questions into SQL queries, executes them, and returns clean, readable answers — all from a friendly web UI.

---

## 🚀 Features
- **🔄 Dual Database Support**
  - SQLite (`student.db`)
  - MySQL (via secure credentials)
- **💬 Natural Language Queries**
  - Ask questions like *"Show all students scoring above 80 marks"*.
- **🧠 LangChain SQL Agent**
  - Uses `SQLDatabaseToolkit` and `AgentType.ZERO_SHOT_REACT_DESCRIPTION`.
- **⚡ Powered by Groq’s Llama3 Model**
  - Fast and efficient LLM responses.
- **🌐 Streamlit Web Interface**
  - Sidebar DB selection, chat history, and live query results.
- **🔐 Secure Inputs**
  - MySQL credentials and API keys are never hardcoded.

---

## 🛠 Tech Stack
- **Python 3.10+**
- **Streamlit** – Web app framework
- **LangChain** – LLM orchestration
- **Groq API** – Llama3 model integration
- **SQLite** – Local DB storage
- **MySQL** – Remote DB support
- **SQLAlchemy** – Database connectivity

---
