# n8n-automations

# 🚀 My n8n Automation Workflows

Welcome to my central repository for **n8n automation workflows**. This repository contains a collection of production-ready and experimental automations designed to streamline business processes, integrate AI models, and connect various cloud services.

Whether it's managing leads, integrating LLMs (Large Language Models), or automating daily tasks, you'll find the complete workflow blueprints (`.json` files) here.

---

## 🛠️ Tech Stack & Integrations
Here are some of the core tools and nodes I frequently use in these workflows:
* **AI & LLMs:** Groq (Llama 3.3), OpenAI (ChatGPT), 
* **Google Ecosystem:** Google Sheets, Google Drive, Gmail
* **Databases & CRMs:** Airtable, PostgreSQL, Notion
* **Utilities:** Webhooks, HTTP Requests, IF/Switch Logic, Code Nodes (JS/Python), Apify, Slack

---

## 📂 Repository Structure

Every folder contains the exported `.json` file of the workflow along with a dedicated setup guide.

| # | Workflow Name | Description | Key Nodes Used |
|---|---|---|---|
| 1 | [Lead Auto-Qualifier](./01-lead-auto-qualifier) | Automatically fetches new leads from Google Sheets, uses Groq AI to qualify them (HOT/WARM/COLD), and updates the status back. | Google Sheets Trigger, Groq Chat Model, AI Agent, If Node |


## 🚀 How to Use These Workflows

If you want to replicate any of these workflows in your own n8n instance, follow these simple steps:

1. **Explore:** Navigate to any workflow folder above and open the `workflow.json` file.
2. **Copy Code:** Copy the raw JSON content of the file.
3. **Import to n8n:** * Open your n8n dashboard.
   * Create a new blank workflow.
   * Click on the canvas and press `Ctrl + V` (or `Cmd + V` on Mac) to paste the workflow.
4. **Configure Credentials:** Double-click the nodes that require authentication (e.g., Google OAuth, Groq API, OpenAI) and select your own credentials.
5. **Test & Activate:** Test the triggers and turn the workflow **ON**.

---

## 👤 Connect with Me
If you have any questions, want to collaborate on an automation project, or need help setting these up, feel free to reach out!

* **LinkedIn:** [https://www.linkedin.com/in/muhammad-haseeb-gulll/]
