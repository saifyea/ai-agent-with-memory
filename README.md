# 🤖 RAG-powered AI Customer Support Agent with Memory

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Anthropic](https://img.shields.io/badge/Anthropic-Claude-orange)
![RAG](https://img.shields.io/badge/RAG-Enabled-success)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

An intelligent AI customer support agent built with **Python**, **Anthropic Claude API**, **Retrieval-Augmented Generation (RAG)**, and **Conversational Memory**.

The agent answers customer questions by retrieving information from a custom knowledge base (product catalog, FAQs, and store policies) while remembering previous conversations to provide more natural and context-aware responses.

---

## 🚀 Project Overview

This project simulates a real-world AI customer support assistant for an online business.

Instead of relying only on an LLM, the agent:

- Retrieves relevant business information from a custom knowledge base.
- Maintains conversation history during the session.
- Generates accurate, context-aware responses using Claude.
- Reduces hallucinations by grounding responses in business data.
---

## ✨ Features

- 🤖 AI-powered customer support assistant
- 🧠 Conversational memory for multi-turn interactions
- 📚 Retrieval-Augmented Generation (RAG)
- 🛍️ Product catalog search
- ❓ FAQ retrieval
- 📜 Store policy lookup
- 💬 Context-aware responses using Claude API
- ⚡ Fast and interactive command-line interface
- 🔒 Secure API key management with `.env`

---

## 🏗️ System Architecture

```text
                User Question
                      │
                      ▼
        Load Conversation History
                      │
                      ▼
      Search Knowledge Base (RAG)
      ├── Product Catalog
      ├── FAQ
      └── Store Policy
                      │
                      ▼
      Build Context + Conversation
                      │
                      ▼
          Anthropic Claude API
                      │
                      ▼
            AI Generated Response
                      │
                      ▼
      Update Conversation Memory
```

---

## 📁 Project Structure

```text
ai-agent-with-memory/
│
├── main.py
├── README.md
├── requirements.txt
├── .env.example
│
├── knowledge_base/
│   ├── product_catalog.txt
│   ├── faq.txt
│   └── store_policy.txt
│
└── .gitignore
```
