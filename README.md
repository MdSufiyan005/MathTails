# 🧮 Math-Tails: AI-Driven Storytelling for Math Education

Math-Tails is an AI-powered platform designed to make mathematics engaging and accessible for students from diverse linguistic backgrounds. It combines personalized storytelling, audio narration, and dynamic visualizations to explain mathematical concepts through an interactive web interface.

## 📌 Project Overview

The core objective is to improve mathematical comprehension by:

- Using **Retrieval-Augmented Generation (RAG)** for generating topic explanations and Q&A content.
- Enabling **multi-language support** using advanced TTS (Text-to-Speech) and STT (Speech-to-Text) models.
- Providing **interactive visuals** via Manim, Desmos, and Three.js.
- Supporting **one-on-one teacher-like interaction** using real-time communication services.

---

## 🎯 Key Features

- ✍️ AI-generated math stories tailored to student queries.
- 🎙️ Multilingual narration using **Facebook TTS** and **Eleven Labs**.
- 📊 Step-by-step animated explanations using **Manim** and **Three.js**.
- 🧠 Personalized query handling through **LangGraph** and **RAG pipelines**.
- 📹 Real-time interaction powered by **LiveKit**.
- 📂 Entirely open-source with modular microservices architecture.

---

## 🧠 Tech Stack

**Frontend**: React.js, Tailwind CSS  
**Backend**: Django REST Framework, PostgreSQL  
**AI/ML**:  
- LangGraph for agent orchestration  
- Grok/Other open-source LLMs for generation  
- RAG for contextual content retrieval  
- Facebook TTS / Whisper (STT)  
**Visuals**: Manim, Desmos, Three.js  
**Realtime Engine**: LiveKit  
**Infrastructure**: Docker, CDN, Caching, Message Queues

---

## 🧭 System Design

### 🔹 High-Level Architecture

![High-Level Architecture](Images/Highlevel_Archetecture.png)

> This diagram outlines how different components communicate: frontend sends topic requests, backend orchestrates AI agents, and visual/audio responses are served dynamically.

---

### 🔸 Low-Level Architecture

![Low-Level Architecture](Images/LowLevel_Archetecture.png)

> The lower-level diagram zooms into microservices: personalization engine, visualization pipelines, and modules like caching, Message Queues, etc.

---

## 🎓 Educational Impact

Math-Tails aims to bridge the gap for students who struggle with traditional instruction methods. By combining advanced NLP, multilingual support, and real-time interaction, it offers a scalable solution for inclusive and immersive education.

---

## 📌 Status

🚧 **Work in Progress**  
- System design finalized  
- Working on integration of LangGraph + RAG  
- Real Time Voice Interaction


---

## 🙋‍♂️ Author
Mohammad Sufiyan

