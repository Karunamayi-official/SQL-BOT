# 🦜 Chat with SQL DB  

A simple Streamlit app to **chat with your SQL database** using **LangChain** + **Groq LLM**.  
Supports **SQLite** and **MySQL**. Perfect for data analysts who don’t want to write SQL all day.  

---

## 🚀 Features
- Connect to SQLite (`student.db`) or MySQL  
- Ask questions in plain English → get SQL results  
- SELECT queries show results as a Pandas table  
- Other queries handled by LangChain SQL Agent  
- Chat-style UI with Streamlit  

---

## 🛠️ Setup
Clone the repo and install:
```bash
git clone https://github.com/your-username/sql-chatbot.git
cd sql-chatbot
pip install -r requirements.txt

Run the app:

streamlit run app.py
