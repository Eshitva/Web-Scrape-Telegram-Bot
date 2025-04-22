# 🧠 Telegram AI Q&A Bot using n8n, Supabase, and Gemini

This project is an n8n workflow that creates an intelligent Telegram bot. The bot scrapes content from a user-shared link and answers natural language questions about it using **Google Gemini** via **LangChain**.

## 🚀 Features

- 🔗 Accepts links via Telegram chat.
- 🧠 Extracts and processes web content using LangChain Agents.
- 🤖 Responds intelligently using Gemini-1.5 LLM.
- 💾 Stores content and user queries in Supabase for reuse and logging.
- 🪵 Logs all user interactions for tracking and debugging.

---

## 🧰 Tech Stack

- **n8n** – Visual automation workflow tool
- **Telegram Bot API** – User interaction interface
- **Supabase** – Data storage (scraped content, user activity, logs)
- **Google Gemini** – LLM used via LangChain
- **LangChain** – AI orchestration
- **JavaScript** – Used in `Function` and `Code` nodes

---
