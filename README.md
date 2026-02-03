# Ai-Chatbot
````markdown
# 🛡️ AI Cybersecurity Chatbot (Gemini-based)

An ethical AI-powered **Cybersecurity Chatbot** built using **Google Gemini (Generative AI)**.  
This chatbot is designed to promote **defensive cybersecurity**, awareness, and responsible AI usage while **preventing illegal or unethical assistance**.

---

## 🚀 Features

- 🤖 Powered by **Google Gemini 2.5 Flash Lite**
- 🔐 Focused on **defensive & ethical cybersecurity**
- ⚖️ Blocks hacking-related or illegal requests
- 💬 Interactive terminal-based chat experience
- 🧠 Maintains conversation context using chat history
- 📝 Supports **Markdown-formatted responses**

---

## 🧩 Tech Stack

- Python 3
- Google Generative AI (Gemini)
- IPython Display (Markdown Rendering)

---

## 📦 Installation

Install the required dependency:

```bash
pip install -U google-generativeai
````

---

## 🔑 API Key Setup (Important)

⚠️ **Never expose your API key in public repositories.**

Set your API key as an environment variable.

### Windows:

```bash
set GOOGLE_API_KEY=your_api_key_here
```

### Linux / macOS:

```bash
export GOOGLE_API_KEY=your_api_key_here
```

Then configure it in the code:

```python
import os
genai.configure(api_key=os.getenv("GOOGLE_API_KEY"))
```

---

## ▶️ How to Run

Run the chatbot script:

```bash
python chatbot.py
```

You will see:

```text
--- CYBER SECURITY BOT ONLINE ---
Type 'exit' to end the chat.
```

Start asking cybersecurity-related questions responsibly.

---

## 🚫 Ethical Guardrails

This chatbot:

* Does NOT assist with hacking or illegal activities
* Promotes ethical and defensive cybersecurity practices
* Follows responsible AI usage principles

Any hacking-related request will be politely refused.

---

## 📂 Project Structure

```text
├── chatbot.py
├── README.md
└── requirements.txt (optional)
```

---

## 📌 Use Cases

* Cybersecurity awareness
* University AI projects
* Ethical hacking education (theoretical)
* Defensive security learning
* AI + cybersecurity demonstrations

---

## 🧠 Model Configuration

```python
model_name = "gemini-2.5-flash-lite"
system_instruction = "You are a helpful and ethical AI assistant focused on defensive cybersecurity."
```

---

## 📜 License

This project is intended for **educational and research purposes only**.
Users must comply with **Google Generative AI policies**.

---

## 👤 Author

**Abdul Sami Khan**
Computer Systems Engineering Student
IEEE UITU President

```
```
