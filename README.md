<!-- 
  HOW TO USE:
  1. Create a PUBLIC repo named exactly "slothislazy" (same as your username).
  2. Put this file in it as README.md — it will show on your profile Overview page.
  3. Optional: upload your CV PDF to that repo as "Kevin_Vagan_Djafar_CV.pdf" so the Resume badge works.
-->

<h1 align="center">Hi, I'm Kevin Vagan Djafar 👋</h1>

<p align="center">
  <b>Applied Machine Learning & NLP Engineer</b>
  <br/>
  RAG & LLM systems · Transformer NLP · Computer Vision · Generative-AI automation
  <br/>
  📍 Tangerang, Indonesia · Open to ML / AI Engineer roles
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/kevin-vagan-djafar-a98484254/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:vagankevin@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://github.com/slothislazy/slothislazy/blob/main/Kevin_Vagan_Djafar_CV.pdf"><img src="https://img.shields.io/badge/Resume-111111?style=for-the-badge&logo=readthedocs&logoColor=white" alt="Resume"/></a>
</p>

---

### 🧑‍💻 About me

I'm finishing a **BSc in Computer Science at Bina Nusantara University** (GPA 3.72) and I ship AI systems end to end — from scraping and cleaning data, to training and evaluating models rigorously, to deploying them as bots, dashboards and automated pipelines.

- 🏢 **Software Engineer Intern @ Optimaxx Prima Teknik** — built a self-hosted RAG support chatbot and a generative-AI video pipeline used in production
- 🎓 **Exchange semester @ University of Nottingham Malaysia** (GPA 3.80) — AI Methods, Intelligent Agents, Image Processing
- 🔍 I care about **honest evaluation** — data-leakage checks, multi-seed runs, ablations and strong baselines
- 🌏 Indonesian (native) · English (IELTS 7.5, C1)

---

### 💼 Experience

**Software Engineer Intern — Optimaxx Prima Teknik** · Jakarta · *Aug 2025 – Feb 2026*

- Built a **self-hosted WhatsApp support chatbot** on Ollama (DeepSeek R1) with a RAG pipeline, fully Dockerized — no per-token API cost and no customer data leaving the company network
- Designed **message classification & routing** so staff only saw queries the bot couldn't answer, plus a dashboard for monitoring chat history
- Engineered a **Telegram bot that turns one food photo into a publish-ready 16-second video** (Gemini 2.5 Pro, Veo 3, Gemini TTS) and auto-publishes to YouTube and TikTok
- Replaced a manual registration process with an **AppSheet + Google Sheets** class-management system with automated approvals and email notifications

---

### ⭐ Featured projects

<table>
<tr>
<td width="50%" valign="top">

#### ☕ [Coffee Origin Classification & Recommendation](https://github.com/slothislazy/Coffee-Origin-and-Recommendation)
Thesis project. NLP framework that predicts a coffee's origin from its tasting notes and recommends coffees from a free-text flavor query.

- **85% accuracy / 0.83 macro-F1** on regional origin with a RoBERTa ensemble, trained on **9,009** scraped expert reviews
- Leakage-scrubbing pipeline masking **403 origin-revealing terms** — without it, models "cheat" to 91% by memorizing names
- Dense-retrieval recommender over **BGE & E5** embeddings, benchmarked against TF-IDF and SBERT

`PyTorch` `Transformers` `RoBERTa` `Sentence-Transformers` `Web Scraping`

</td>
<td width="50%" valign="top">

#### 🎬 [Picture-to-Video AI Bot](https://github.com/slothislazy/Picture-to-Video)
Telegram bot that turns one food photo into an edited 16-second vertical promo video — no manual editing.

- **Gemini 2.5 Pro** writes the title, SEO description, video prompts and SRT script as structured JSON
- **Veo 3** generates two clips; **Gemini TTS** narrates; **MoviePy** burns subtitles, adds intros and mixes audio
- Async pipeline with OAuth uploads to **YouTube & TikTok**

`Python` `Gemini API` `Veo 3` `MoviePy` `Telegram Bot API` `OAuth`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 💬 [WhatsApp RAG Chatbot](https://github.com/slothislazy/Whatsapp-Chatbot)
Self-hosted customer-support chatbot running a local LLM with retrieval over a company knowledge base.

- **DeepSeek R1 via Ollama** + RAG, all inference on local hardware
- Query routing that escalates only unanswerable messages to staff, with a monitoring dashboard

`Python` `Ollama` `RAG` `LLM` `Docker` `Docker Compose`

</td>
<td width="50%" valign="top">

#### 📈 [Counter-Strike Market Analyzer](https://github.com/Foxtrox420/Counter-Strike-Market-Analyzer)
Interactive tool that analyzes and forecasts in-game item prices.

- Benchmarked **ARIMA, LSTM and XGBoost** (Optuna-tuned) for time-series forecasting
- Deployed the best model behind a **Gradio** UI for skins, cases, knives and gloves

`XGBoost` `LSTM` `ARIMA` `Optuna` `Gradio`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🚬 [Smoking Detection with YOLOv8](https://github.com/slothislazy/Smoking-Recognition)
Real-time computer vision system that detects smoking in public spaces.

- Trained **YOLOv8** on a custom Roboflow dataset; handled data prep, training and inference code
- Model is live on [Roboflow Universe](https://universe.roboflow.com/three-musketeers/cigarette-detection-2ao2c/model/3)

`YOLOv8` `Ultralytics` `Roboflow` `Computer Vision`

</td>
<td width="50%" valign="top">

#### 💳 [Fraud Detection in E-Commerce](https://github.com/slothislazy/Fraud-Detection-in-E-Commerce)
Supervised models to flag fraudulent online purchases from customer, payment, device and browser features.

- Merged several public transaction datasets into one training set, with probabilistic imputation for missing values
- Trained **Random Forest** and **XGBoost** classifiers

`R` `Random Forest` `XGBoost` `Statistics`

</td>
</tr>
</table>

<details>
<summary><b>More projects</b></summary>
<br/>

- **5G Impact on the Gaming Industry** — interactive dashboard linking 5G coverage, network latency and gaming adoption, from live packet capture (Scapy) to geospatial maps (Folium, Plotly)
- **Face Recognition with LBPH** — real-time celebrity identification system using OpenCV's Local Binary Pattern Histogram recognizer
- **Flower Segmentation Pipeline** — benchmarked color-space conversion, thresholding and morphological operations in OpenCV to improve segmentation accuracy

</details>

---

### 🛠️ Tech stack

**Languages**
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white"/>
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white"/>
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white"/>
  <img src="https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white"/>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>
</p>

**Machine Learning & AI**
<p>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black"/>
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white"/>
  <img src="https://img.shields.io/badge/XGBoost-189FDD?style=flat-square"/>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white"/>
  <img src="https://img.shields.io/badge/YOLOv8-111F68?style=flat-square"/>
  <img src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white"/>
  <img src="https://img.shields.io/badge/Google%20Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white"/>
</p>

**Tools & Platforms**
<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white"/>
  <img src="https://img.shields.io/badge/Gradio-F97316?style=flat-square"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Alibaba%20Cloud-FF6A00?style=flat-square&logo=alibabacloud&logoColor=white"/>
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white"/>
</p>

---

### 📜 Certifications

| Certification | Issuer | Date |
|---|---|---|
| ACA Cloud Computing | Alibaba Cloud | May 2024 |
| Machine Learning with Python | freeCodeCamp | Jun 2024 |
| IELTS Academic — Band 7.5 (C1) | IELTS | Jun 2024 |
| Go: The Complete Developer's Guide | Udemy | Aug 2026 |

---

<p align="center">
  <i>Always happy to talk about NLP, LLM systems or computer vision — feel free to reach out.</i>
</p>
