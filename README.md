# Lalah – Afghan Educational Chatbot

Lalah is a multilingual educational chatbot designed for Afghan students and teachers.  
It supports **Dari**, **Pashto**, and **English**, and runs on WhatsApp, web, and other channels to provide 24/7 learning support.

Lalah helps learners practice reading, writing, comprehension, Kankor preparation, and more, using modern AI technologies combined with local curriculum needs.

---

## 🌱 Why Lalah?

Many Afghan students have:

- Limited access to quality teachers and learning materials  
- Unstable internet and expensive data  
- Very little personalized support or feedback  

Lalah tries to reduce this gap by providing:

- A **24/7 AI tutor** in Dari, Pashto, and English  
- Simple text-based interaction (works even with low bandwidth)  
- Content aligned with Afghan school subjects and Kankor preparation  

---

## ✨ Key Features

- **Multilingual support**
  - Understands and responds in Dari, Pashto, and English
  - Handles mixed-language messages where possible

- **Educational focus**
  - Reading and comprehension practice
  - Writing support and feedback
  - Science, math, and general knowledge
  - Kankor exam preparation (Afghan university entrance)

- **RAG (Retrieval-Augmented Generation)**
  - Uses a curated knowledge base for more accurate answers
  - Can be customized with new documents and content

- **WhatsApp & Web**
  - Accessible through WhatsApp (chatbot style)
  - Web interface for testing and future integrations

- **Personalized support**
  - Session-based memory to follow ongoing conversations
  - Safer responses for students (content filters and rules)

---

## 🧠 Tech Stack

Lalah is built using:

- **LLMs**
  - OpenAI models
  - Google Gemini models

- **Orchestration**
  - [LangChain] for chaining tools, prompts, and RAG

- **Retrieval & Memory**
  - **ChromaDB** for vector search (RAG)
  - **Redis** for session-based chat history

- **Backend**
  - Python
  - Flask (web server and webhooks)

- **Infrastructure**
  - AWS EC2 (current deployment)
  - Redis (AWS ElastiCache)

- **Integrations**
  - WhatsApp Business API (via webhook)
  - Web frontend (simple chat UI)

> Note: This repository currently focuses on documentation and project overview. Code structure and deployment instructions will be added in next versions.

---

## 🎯 What Lalah Can Do (Use Cases)

For **students**:

- Ask questions about school subjects in Dari, Pashto, or English  
- Practice reading and comprehension with guided questions  
- Get help understanding difficult topics step by step  
- Prepare for **Kankor** with explanations and sample questions  

For **teachers / organizations**:

- Provide an always-available assistant for their learners  
- Add their own learning materials into Lalah using RAG  
- Support remote and blended learning programs  
- Use analytics (future feature) to see common questions and needs  

---

## 🔒 Safety & Student Protection

Lalah includes a custom safety layer for:

- Detecting inappropriate or harmful questions  
- Blocking or redirecting unsafe content  
- Limiting off-topic or non-educational requests  
- Handling attacks like prompt injection where possible  

These checks are being improved continuously for **Dari**, **Pashto**, and **English**.

---

## 🛠 Current Status

- Deployed version running on **AWS EC2 t3.xlarge**
- Integrated with **Redis** and **ChromaDB**
- Connected to **WhatsApp** for pilot users
- Tested with Afghan students in real educational use cases

Planned improvements:

- Cleaner modular codebase for public release  
- Better language detection for short text in Arabic script  
- More structured learning paths (lessons, levels, quizzes)  
- Dashboard/analytics for partners (schools, universities, NGOs)  

---

## 🚀 Roadmap (High Level)

- [ ] Open-source selected components of Lalah  
- [ ] Add example data and RAG setup scripts  
- [ ] Provide Docker-based deployment template  
- [ ] Add Telegram and web-widget integrations  
- [ ] Release documentation for partners (schools, NGOs)  

---

## 🤝 Collaboration & Partnerships

Lalah is built for Afghan students and institutions.  
If you are:

- A school, university, or NGO
- Working on education in Afghanistan or similar contexts
- Interested in piloting or integrating Lalah

you are welcome to reach out and discuss collaboration.

---

## 📫 Contact

- **Project lead:** Shams Haqyar  
- **Email:** Shams.haqyar786@gmail.com  
- **Website:**  https://senf.af/lalah.html
- **WhatsApp demo :** https://wa.link/78knlw

---

## 📄 License

> (Choose a license and update this section, for example MIT, Apache 2.0, or “All rights reserved”)

Example:

This project is currently **closed source**.  
Code and models are not yet publicly available, but the high-level design and documentation can be used for learning and discussion.

