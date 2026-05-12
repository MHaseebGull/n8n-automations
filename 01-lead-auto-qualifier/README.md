# 📊 Lead Auto-Qualifier Workflow

This n8n workflow automatically monitors a Google Sheet for new leads, qualifies them using Groq AI (Llama 3.3), and updates the sheet with the classification response.

## How it works:
1. **Google Sheets Trigger:** Triggers every time a new row (lead) is added.
2. **AI Agent (Groq):** Evaluates the lead's message and classifies it as HOT, WARM, or COLD based on system prompts.
3. **If Node:** Routes the workflow logic based on the AI output.
4. **Update Row in Sheet:** Saves the AI's classification and analysis back into the original Google Sheet.

## Setup Requirements:
* n8n instance (Self-hosted or Cloud)
* Google Sheets OAuth2 credentials
* Groq API Key (with Llama-3.3-70b-versatile model active)
