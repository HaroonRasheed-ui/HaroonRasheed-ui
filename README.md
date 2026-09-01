<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=25&duration=2800&pause=1000&color=36BCF7&center=true&vCenter=true&width=650&height=50&lines=Hi%2C+I%27m+Haroon+Rasheed+%F0%9F%91%8B;AI+%26+Automation+Engineer+%F0%9F%A4%96;OCR+%2B+LLM+Pipeline+Builder+%F0%9F%93%84;n8n+Workflow+Automation+%E2%9A%99%EF%B8%8F" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://python.org"><img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" /></a>
  <a href="https://fastapi.tiangolo.com"><img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" /></a>
  <a href="https://n8n.io"><img src="https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white" /></a>
  <a href="https://langchain.com"><img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=chainlink&logoColor=white" /></a>
  <a href="https://openai.com"><img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" /></a>
  <a href="https://opencv.org"><img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" /></a>
  <a href="#"><img src="https://img.shields.io/badge/PaddleOCR-00A1D6?style=for-the-badge" /></a>
  <a href="https://docker.com"><img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" /></a>
</p>

I'm an **AI & Automation Engineer** from Pakistan, focused on building production-grade generative AI systems, OCR/computer-vision pipelines, and business automation workflows. I hold a BS in Artificial Intelligence and have hands-on experience integrating LLMs and CV models into real-world products that clients actually run in production.

I work across the full stack — from prompt/system-prompt design, to OCR and RAG pipelines, to REST API backends and n8n automations that wire everything together.

---

## 💼 What I Do

- 📄 **Document Intelligence / OCR pipelines**: high-throughput extraction from scanned business documents using PaddleOCR + OpenVINO acceleration
- 🤖 **LLM-powered chatbot development** with multi-turn memory, intent recognition, and contextual reasoning
- 🔍 **RAG / retrieval pipeline** design and deployment
- ⚡ **Business process automation** with n8n, connecting LLMs to APIs, databases, and webhooks
- ✍️ **Prompt & system-prompt engineering** for real-world production use cases
- 👁️ **Computer vision**: real-time object detection, OCR-based text reading, gesture/plate recognition
- 🧠 **ML/DL for NLP & audio**: intent recognition, NER, text classification, sentiment & speech-emotion analysis

---

## 🛠️ Tech Stack

**AI & LLMs:** OpenAI (GPT-4 / GPT-3.5), Anthropic (Claude), Google (Gemini), Hugging Face Transformers
**OCR & Computer Vision:** PaddleOCR, OpenVINO, OpenCV, YOLOv8
**Automation:** n8n, LLM-to-API/database wiring, REST APIs, webhooks, third-party integrations
**Languages & Backend:** Python, SQL, FastAPI, Flask
**ML / DL & NLP:** TensorFlow, Scikit-learn, Keras, Pandas, NumPy · CNN, RNN, LSTM, Transformer, ViT
**Tools:** Git, GitHub, Docker (basic), Postman, VS Code
**Integrations:** Stripe, QuickBooks Online, Google APIs, SMTP/Mail services

---

## 🚀 Selected Projects

> 🔒 Most client/production repos are private. Descriptions reflect live, deployed work.

### 📄 HaeirLens OCR Based Data Exctraction — Intelligent Document Processing Pipeline
Production OCR pipeline for Haier Pakistan Delivery Notes & Gate Passes, extracting Customer No, DN No, model codes, serial numbers, and item numbers.
- Rearchitected from a job-queue/SQLite/dashboard model into a single synchronous `POST /extract → immediate result` FastAPI endpoint
- ~0.26s/region throughput using PaddleOCR PP-OCRv6_tiny + OpenVINO HPI acceleration, with parallel page processing via ThreadPoolExecutor
- Custom table-boundary detection, anchor-based row grouping, continuation-page numbering, and handwritten-stamp noise suppression

---

### 💱 Cross-System Reconciliation Automation (n8n + Python)
Scheduled automation pipeline pulling data from Stripe and QuickBooks Online via their APIs, matching transactions and surfacing only discrepancies — replacing a manual multi-hour reconciliation process with a hands-off daily run used by a real client.
- Built on n8n, integrating QuickBooks Online and Claude AI
- Drastically reduced manual processing time per reconciliation cycle
- Deployed in production; exceptions-only reporting surfaces what matters

---

### 🎙️ [NeuraSense — Speech Emotion Recognition](https://github.com/HaroonRasheed-ui/NeuraSense-Speech-Emotion-Recognition-System)
Deep learning system recognizing human emotion from speech in real time.
- CNN + Bidirectional LSTM + Multi-Head Attention architecture
- Real-time inference pipeline for continuous audio streams

---

### 👓 [AI Smart Glasses for the Visually Impaired](https://github.com/HaroonRasheed-ui/AI-Smart-Glasses-Visually-Impaired-People)
Assistive wearable with real-time YOLOv8 obstacle detection and spatial audio guidance (English/Urdu), plus OCR-based text reading.
- Edge-deployable pipeline with optional Arduino/GPS hardware integration
- OCR + TTS pipeline for intuitive, voice-based alerts

---

### 🗣️ Hamer AI Assistant — Assistive Voice Conversational AI
Multi-modal (voice + text) AI assistant with real-time LLM responses, multi-turn memory, and tool-use/contextual reasoning for complex, multi-step queries.
- Built with Python, LangChain, and OpenAI APIs
- ReAct-style agentic pipeline for autonomous multi-step reasoning

---

## 📌 Current Focus

- 📄 Production OCR/IDP pipelines and document-intelligence throughput optimization
- 🧠 Advanced LLM agent design and multi-agent orchestration
- 🔍 Production RAG pipelines and retrieval optimization
- 🏢 Enterprise AI automation and business workflow integration (ERP/HRMS-adjacent)

---

## 🎓 Education & Certifications

**BS in Artificial Intelligence** — The University of Haripur, KPK, Pakistan (2021 – 2025)

- Data Science & AI Internship — CodXo (2024)
- AI Engineering Internship — EcodeCamp (2024)
- Data Analytics Externship — Beats by Dre (2024)

---

## 📊 GitHub Activity

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=HaroonRasheed-ui&theme=react-dark&hide_border=true" alt="Haroon's Contribution Graph" width="100%" />
</p>

<p align="center">
  <img src="./profile/stats.svg" alt="GitHub Stats" width="48%" />
  <img src="./profile/top-langs.svg" alt="Top Languages" width="48%" />
</p>

<p align="center">
  <img src="./profile/streak.svg" alt="GitHub Streak" width="80%" />
</p>

### 🏆 Trophies

<p align="center">
  <img src="https://github-trophies.devomb.com/?username=HaroonRasheed-ui&theme=darkhub&no-frame=true&row=1&column=6" alt="Trophies" />
</p>

### 🐍 Contribution Snake

<p align="center">
  <img src="https://raw.githubusercontent.com/HaroonRasheed-ui/HaroonRasheed-ui/output/github-contribution-grid-snake.svg" alt="Snake animation" width="100%" />
</p>

> ⚠️ The snake animation only renders once the GitHub Action in `snake.yml` (included alongside this file) has run at least once on your profile repo — see setup notes below.

---

## 📬 Connect With Me

- 📧 Email: [haroon5253rasheed@gmail.com](mailto:haroon5253rasheed@gmail.com)
- 💼 LinkedIn: [Haroon Rasheed](https://www.linkedin.com/in/haroon-rasheed-383768375)
- 📞 WhatsApp: [+92 324-0829682](https://wa.me/923240829682)
- 📍 Charsadda, KPK, Pakistan · **Open to Remote**

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=HaroonRasheed-ui&color=0e75b6&style=for-the-badge&label=PROFILE+VIEWS" alt="Profile Views" />
</p>
