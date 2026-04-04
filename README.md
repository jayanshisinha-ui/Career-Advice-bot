# 🤖 AI Career Guidance Chatbot using n8n and OpenAI GPT

![n8n](https://img.shields.io/badge/Built%20With-n8n-orange)
![OpenAI](https://img.shields.io/badge/AI-OpenAI%20GPT-green)
![Google Sheets](https://img.shields.io/badge/Database-Google%20Sheets-blue)
![Automation](https://img.shields.io/badge/Type-Automation-yellow)

---

## 📌 Project Overview

This project is an **AI-powered Career Guidance Chatbot** built using the **n8n workflow automation platform** and **OpenAI GPT**.

The chatbot provides career suggestions and answers frequently asked questions using structured data stored in **Google Sheets**. It uses an **AI Agent** to process user queries and generate intelligent responses, along with **memory functionality** to maintain conversation context.

This project demonstrates how **AI-powered chatbots** can be created using **no-code/low-code tools** without traditional backend development.

---

## 🚀 Features

✔️ AI-powered chatbot for career guidance  
✔️ Retrieves career and FAQ data from Google Sheets  
✔️ Generates responses using OpenAI GPT  
✔️ Maintains conversation memory  
✔️ Fully automated workflow using n8n  
✔️ Handles structured knowledge base queries  
✔️ No traditional coding required  

---

## 🛠️ Technologies Used

- 🔶 **n8n** — Workflow Automation Platform  
- 🤖 **OpenAI GPT** — AI Response Generation  
- 📄 **Google Sheets** — Knowledge Base Storage  
- 🧠 **Simple Memory Node** — Conversation Memory  
- ⚙️ **AI Agent Node** — Query Processing  

---

## 🔄 Workflow Architecture

The chatbot follows this workflow:

1️⃣ **When Chat Message Received** — Trigger starts workflow  
2️⃣ **AI Agent** receives user query  
3️⃣ Data is retrieved from:

- 📄 Career Information Sheet  
- ❓ FAQ Information Sheet  

4️⃣ Query is processed using **OpenAI GPT**  
5️⃣ Response is generated and returned to the user  
6️⃣ Memory stores conversation history  

---


### 📄 Career Information Sheet

| Career Name | Description | Required Skills | Salary Range |
|-------------|-------------|----------------|---------------|
| Data Scientist | Works with data and machine learning | Python, Statistics | ₹6–15 LPA |
| Web Developer | Builds websites and applications | HTML, CSS, JavaScript | ₹3–10 LPA |

---

### ❓ FAQ Information Sheet

| Question | Answer |
|----------|--------|
| What is AI? | Artificial Intelligence enables machines to simulate human intelligence. |
| Which career is best after BCA? | Careers like Web Development, Data Science, and Software Development are popular choices. |

---

