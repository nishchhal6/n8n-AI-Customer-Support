# AI eCommerce Support Agent (Event-Driven Pipeline) 🚀

An automated, intelligent customer support routing system built using **n8n** and **Google Gemini AI**. 

## 🧠 System Architecture
This project uses an **Agentic Workflow** (Deterministic Routing) rather than an autonomous agent to ensure 100% enterprise safety and eliminate AI hallucination risks in customer-facing environments.

### How it works:
1. **Webhook Trigger:** Intercepts incoming customer support emails/tickets.
2. **AI Analysis (Google Gemini):** Extracts `Sentiment`, `Urgency`, and generates an `AI Draft Reply`.
3. **JSON Parsing:** Converts LLM text output into structured data for routing.
4. **Conditional Routing (Switch):** - 🚨 **If Angry/High Urgency:** Instantly escalates to the Human Support Team via VIP Email Alert.
   - 📧 **If Neutral/Positive:** Automatically sends the AI-generated draft back to the customer.

## 🛠️ Tech Stack
* **n8n** (Workflow Automation, Webhooks, Conditional Logic)
* **Google Gemini 2.5 Flash API** (Sentiment Analysis & Prompt Engineering)
* **REST APIs & JSON Data Handling**

## 📸 Workflow Preview
*<img width="1659" height="873" alt="image" src="https://github.com/user-attachments/assets/7e26108e-ca3d-40cd-9fa9-ff64b372d265" />
*
