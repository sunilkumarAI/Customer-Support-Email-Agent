# 📧 Customer Support Email Agent

An AI-powered customer support automation built with **n8n** that monitors incoming Gmail messages, identifies genuine customer support requests, retrieves relevant company information from a knowledge base using Retrieval-Augmented Generation (RAG), generates professional responses with an LLM, and automatically replies to customers.

---

## 🚀 Features

* 📥 Automatically monitors incoming Gmail messages
* 🧠 AI-based email classification
* 🤖 Human-like email replies using Google Gemini
* 📚 RAG-powered responses using Pinecone Vector Database
* 🔍 Semantic search with OpenAI Embeddings
* 🏷️ Automatically labels processed emails
* 📤 Sends professional replies automatically
* ⚡ Fully automated end-to-end workflow

---

## 🛠 Tech Stack

* **n8n**
* **Google Gmail API**
* **Google Gemini 3.1 Flash Lite**
* **OpenRouter**
* **Pinecone Vector Database**
* **OpenAI Embeddings**
* **Retrieval-Augmented Generation (RAG)**

---

## 📌 Workflow Overview

```
Incoming Gmail
      │
      ▼
 Gmail Trigger
      │
      ▼
AI Text Classifier
      │
      ▼
Customer Support?
      │
      ▼
AI Agent
      │
      ├── Query Pinecone Knowledge Base
      │
      ▼
Generate Context-Aware Reply
      │
      ▼
Add Gmail Label
      │
      ▼
Send Email Reply
```

---

## ⚙️ How It Works

1. Gmail Trigger continuously monitors new incoming emails.
2. AI Text Classifier determines whether the email is a customer support request.
3. The AI Agent analyzes the customer's issue.
4. If policy or product information is required, the agent retrieves relevant context from the Pinecone Vector Database.
5. Google Gemini generates a natural, professional response.
6. The workflow labels the processed email.
7. The generated reply is automatically sent back to the customer.

---

## 📂 Project Structure

```
Customer-Support-Email-Agent/
│
├── workflow.json
├── README.md
└── screenshots/
    ├── workflow.png
    └── demo.gif
```

---

## 📸 Screenshots

Add screenshots of:

* Complete n8n workflow
* Workflow execution
* Sample generated email reply

---

## 💡 Use Cases

* E-commerce customer support
* SaaS support automation
* Product inquiries
* Order tracking
* Refund and return requests
* FAQ automation
* Customer service teams

---

## 🔮 Future Improvements

* Multi-language support
* Human approval before sending responses
* CRM integration (HubSpot, Salesforce)
* Ticket creation (Zendesk, Freshdesk)
* Slack or Microsoft Teams notifications
* Analytics dashboard
* Sentiment analysis
* Conversation history and memory

---

## 👨‍💻 Author

**B Sunil Kumar**

Final Year Engineering Student

Passionate about Agentic AI, Workflow Automation, and Building Real-World AI Solutions.

---

⭐ If you found this project useful, consider giving it a star!
