# 🤖 LinkedIn Content Creator Agent (n8n Workflow)

This project contains an **n8n workflow** that automatically generates LinkedIn content ideas using AI, fetches relevant info via an API (Tavily), and stores everything in Google Sheets. Ideal for creators, marketers, and businesses.

---

## 🧠 Workflow Features

- ✅ Reads tasks from a Google Sheet (where `Status = todo`)
- 🔍 Sends a query to the Tavily Search API to retrieve relevant context
- 🤖 Uses an AI Agent (OpenRouter + LangChain) to generate content
- ✍️ Writes the content back to the Google Sheet with `Status = created`

---

## 🛠️ Requirements

- [n8n](https://n8n.io/) installed (locally or hosted)
- Access to:
  - Google Sheets API (OAuth2 credentials)
  - Tavily API key (https://app.tavily.com/)
  - OpenRouter API key (https://openrouter.ai/)
- Your own Google Sheet for tracking tasks

---

## 📦 Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
