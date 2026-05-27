# 🚀 AI-Powered LinkedIn Content Automation Workflow

## 📌 Overview

This project is an AI-powered automation system that generates and publishes LinkedIn posts automatically using:

- n8n (Workflow Automation)
- Google Sheets
- Gemini AI (Google AI Model)
- LinkedIn API

It eliminates manual effort in content creation and posting by fully automating the workflow from input to publication.

---

## 🎯 Problem Statement

Creating LinkedIn posts manually involves:

- Writing content from scratch
- Formatting and adding hashtags
- Posting manually every time
- Maintaining consistency

This process is time-consuming and repetitive.

---

## 💡 Solution

This project automates the entire workflow using AI and automation tools:

- Takes input from Google Sheets
- Generates professional posts using AI (Gemini)
- Formats content automatically
- Publishes directly to LinkedIn

---

## 🔄 Workflow Architecture

Below is the implemented n8n automation workflow:

![AI LinkedIn Automation Workflow](image(4).png)

### Flow Explanation:

Google Sheets → n8n Trigger → Basic LLM Chain (Gemini AI) → Content Processing → LinkedIn Post Creation

---

## 🛠️ Tech Stack

- **n8n** – Workflow automation platform  
- **Google Sheets** – Input data source  
- **Gemini AI** – Content generation model  
- **LinkedIn API** – Post publishing  

---

## ⚙️ How It Works

1. Add a topic or content idea in Google Sheets  
2. n8n detects new/updated data (Trigger Node)  
3. Gemini AI generates a LinkedIn post  
4. Content is refined and formatted  
5. Final post is published to LinkedIn automatically  

---

## 🧩 Key Features

- Fully automated LinkedIn post generation  
- AI-powered content creation  
- No-code workflow using n8n  
- Real-time automation  
- Scalable design for future platforms  

---

## 📅 Trigger Types

- Manual Trigger (testing phase)  
- Event-based Trigger (Google Sheets update)  
- Scheduled Trigger (time-based automation)  

---

## 🧠 What I Learned

- Building end-to-end AI workflows using n8n  
- Integrating Google Gemini AI into automation systems  
- API-based automation (LinkedIn integration)  
- Designing scalable workflow architectures  

---

## ⚠️ Challenges Faced

- Configuring LinkedIn API authentication  
- Optimizing AI prompts for better output  
- Handling workflow debugging in n8n  
- Managing API limits and responses  

---

## 🚀 Future Improvements

- Multi-platform posting (Twitter, Instagram, etc.)  
- Dashboard for content management  
- Analytics for post performance  
- Smarter AI prompt optimization loop  

---

## 📸 Workflow Preview

![Workflow](image(4).png)

---

## 👨‍💻 Author

**Anvitha P**  
BTech Computer Science Engineering  
Sri Vasavi Engineering College  

---

## ⭐ Outcome

This project demonstrates how AI and workflow automation can eliminate manual social media tasks and improve productivity using modern tools like n8n and Gemini AI.
