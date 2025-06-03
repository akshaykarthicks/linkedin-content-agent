🤖 LinkedIn Content Creator Agent (n8n Workflow)
This project contains an n8n workflow that automatically generates LinkedIn content ideas using AI, fetches relevant info via an API (Tavily), and stores everything in Google Sheets. Ideal for creators, marketers, and businesses.

🧠 Workflow Features
✅ Reads tasks from a Google Sheet (where Status = todo)

🔍 Sends a query to the Tavily Search API to retrieve relevant context

🤖 Uses an AI Agent (OpenRouter + LangChain) to generate content

✍️ Writes the content back to the Google Sheet with Status = created

🛠️ Requirements
n8n account (cloud or self-hosted)

Access to:

Google Sheets API (OAuth2 credentials)

Tavily API key (https://app.tavily.com/)

OpenRouter API key (https://openrouter.ai/)

Your own Google Sheet for tracking tasks

🚀 How to Use
Log in to your n8n web interface.

Import the workflow JSON file (provided in this repo).

Configure your credentials for Google Sheets, Tavily API, and OpenRouter API.

Activate the workflow to start automating LinkedIn content creation!

MY WORKFLOW 
![image](https://github.com/user-attachments/assets/76c8975e-08d1-49d4-89cc-4c3a3d14ee34)
or 
![image](https://github.com/user-attachments/assets/3f4dbef3-c046-4f53-8200-0f83961a83b3)

