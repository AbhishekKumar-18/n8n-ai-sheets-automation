# 🚀 Automated n8n AI Workflow

An automated workflow built with **n8n** that integrates Google Sheets with AI Models (OpenAI/Gemini) to seamlessly process, manipulate, and structure data.

---

## 📌 Project Overview
This project automates data retrieval and processing using n8n workflows. It fetches responses from Google Sheets, feeds them into AI models for reasoning or context generation, and maintains short-term memory during execution.

### Key Features
* 📊 **Google Sheets Integration:** Reads and updates row data dynamically.
* 🤖 **AI Powered:** Leverages Large Language Models (LLMs) to analyze and generate structured responses.
* 🧠 **Memory Retention:** Uses buffer window memory to maintain conversational/execution context.
* ⚡ **Fully Automated:** Runs seamlessly without manual intervention.

---

## 🛠️ Tech Stack & Nodes Used
* **Automation Platform:** [n8n](https://n8n.io/)
* **AI & LLMs:** `@n8n/n8n-nodes-langchain.lmChatOpenAi`
* **Memory:** `@n8n/n8n-nodes-langchain.memoryBufferWindow`
* **Database / Trigger:** `Google Sheets Tool`

---

## 📸 Workflow Architecture
*(Replace the image link below with your workflow screenshot)*

![n8n Workflow Architecture](https://via.placeholder.com/800x400?text=Upload+Your+n8n+Workflow+Screenshot+Here)

---

## 🚀 How to Import and Use

1. **Prerequisites:**
   * An active **n8n** instance (Cloud or Self-hosted).
   * Google Cloud Platform Credentials (with Google Sheets & Drive API enabled).
   * API Key for OpenAI / Gemini.

2. **Setup Steps:**
   * Clone this repository:
     ```bash
     git clone [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git)
     ```
   * Open your n8n canvas dashboard.
   * Click on the **3 dots (...)** menu on the top right and select **Import from File**.
   * Upload the `My workflow.json` file provided in this repository.
   * Re-connect your **Google Sheets** and **OpenAI/Gemini** credentials in the node parameters.
   * Execute and test the workflow!

---

## 🔒 Security & Privacy Note
All private credentials, API keys, and sensitive Spreadsheet IDs have been removed or replaced with environment variables/placeholders for security compliance.
