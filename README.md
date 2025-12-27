# Basic Agent with Memory

Simple AI chatbot built with Streamlit and LangChain that demonstrates how to implement conversational memory using a local Large Language Model (LLM).

## 📌 Project Description

This project implements a basic conversational AI agent with memory, allowing the model to retain and use previous messages during the interaction.  
The application uses **LangChain** for prompt management and memory handling, **Ollama** to run a local LLM, and **Streamlit** to provide a simple web interface.

The main goal of this project is to explore how conversational context can be stored and reused to improve response coherence in AI-powered chat applications.

---

## 🧠 Key Features

- Conversational agent with memory
- Manual handling of chat history
- Prompt templating with conversation context
- Local LLM execution using Ollama
- Simple and interactive Streamlit UI

---

## 🛠️ Technologies Used

- Python
- Streamlit
- LangChain
- Ollama (local LLM)
- Prompt Engineering

---

## 🚀 How It Works

1. User inputs a message through the Streamlit interface.
2. Previous conversation history is retrieved from session memory.
3. A prompt is dynamically generated including the full chat context.
4. The local LLM (via Ollama) generates a response.
5. Both user input and AI response are stored in memory for future turns.

---

## ▶️ How to Run the Project

You can visit the (deployed version)[https://basic-agent-with-memory.streamlit.app/] or run it in local following the next steps:

### 1. Clone the repository
```bash
git clone https://github.com/DataSciGina/basic-agent-with-memory.git
cd basic-agent-with-memory
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Make sure Ollama is running and the model is available

```bash
ollama pull mistral
```

### 4. Run the Streamlit app

```bash
streamlit run agent.py
```

## 📚 Learning Objectives

- Understand how conversational memory works in LLM-based agents
- Learn basic prompt engineering techniques
- Explore LangChain memory utilities
- Build simple AI-powered interfaces with Streamlit

## 📌 Notes

This project was developed as part of a hands-on learning exercise focused on AI agents and conversational memory.
It is intended as an educational example rather than a production-ready system.

## 👤 Author

Agostina Ailén Fernández Rodríguez
