# 🧠 Memory-Enabled AI Chatbot using LangChain + Groq

This project implements a conversational AI chatbot powered by **Groq’s Llama 3.1 model** with **persistent memory** using LangChain.  
Each chat session maintains its own conversation history, allowing the bot to remember user details (like name, preferences, etc.) across multiple messages.

---

## 🚀 Features

### ✔ **Session-based memory**
- Every session (`session_id`) has its own stored message history.
- The bot remembers past user inputs within the same session.
- Switching the session clears memory automatically.

### ✔ **Powered by Groq (Llama 3.1)**
- Extremely fast inference.
- High-quality responses.

### ✔ **LangChain message history integration**
- Uses:
  - `ChatMessageHistory`
  - `RunnableWithMessageHistory`
  - `MessagesPlaceholder`

### ✔ **Dynamic language selection**
- Responses follow the language provided in the prompt (e.g., `"Hindi"`).

---

## 🛠️ Tech Stack

- **Python 3**
- **LangChain**
- **Groq API**
- **ChatGroq**
- **ChatMessageHistory**
- **RunnableWithMessageHistory**
