
# Project 01 | Quiz Assigned Notifier 🚀
> An AI-powered email automation workflow built with **n8n**, **Gmail API**, and **Google Gemini AI** to automatically detect quiz assignments, extract deadlines, and send structured notifications.

---

## 📌 Problem Statement
Managing academic deadlines, LMS alerts, and incoming notification emails manually can lead to missed assignments, scattered information, and unnecessary stress. 

## 💡 Solution
This automation workflow connects your Gmail inbox with Google Gemini AI via n8n. It reads incoming notifications, intelligently extracts quiz titles and deadlines, and generates clean status reports.

---

## 🛠️ Tech Stack
* **Workflow Automation:** [n8n](https://n8n.io/)
* **AI Model:** Google Gemini AI (LangChain integration)
* **Integration Nodes:** Gmail API, Manual/Webhook Trigger

---

## ⚙️ How It Works
1. **Trigger:** Initiates via a manual trigger or scheduled poll of incoming Gmail messages.
2. **Fetch Email:** Pulls the latest unread emails matching academic notification criteria.
3. **AI Extraction:** Passes the raw email body to the Gemini AI Agent node to parse specific details (Subject Name, Quiz Title, Submission Deadline).
4. **Action / Report:** Generates a structured summary report ready for notification deployment.

---

## 🚀 Setup & Import Instructions
1. Download the [`quiz-assigned-notifier-workflow.json`](./quiz-assigned-notifier-workflow.json) file from this repository.
2. Open your self-hosted or cloud **n8n** dashboard.
3. Click on **Workflows** -> **Import from File** and select the JSON file.
4. Connect your **Gmail Credential** and **Google Gemini API Key** nodes.
5. Save and execute your workflow!

---

## 🔗 Connect
* **LinkedIn Post:** [View Project Showcase on LinkedIn](https://lnkd.in/p/dXVC5C8T)
