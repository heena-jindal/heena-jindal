# Hi, I'm Heena Jindal 👋

**B.Tech student (AI & ML) building RAG and agentic AI systems.**
Python · LangGraph · ChromaDB · Groq · Flask · Next.js

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/heena-jindal)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/heena-jindal-46581231a/)
[![Portfolio](https://img.shields.io/badge/Portfolio-6C63FF?style=for-the-badge&logo=google-chrome&logoColor=white)](https://heena-portfolio-ten.vercel.app/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hjindal918@gmail.com)

Open to AI / GenAI internships.

---

## Featured projects

### 🎬 [Study-Material-to-Video Agent](https://github.com/heena-jindal/ai-study-video-generator)
A multi-agent LangGraph pipeline that turns a topic into a narrated, animated explainer video.

- **Planner → Narration → Visual → Assembler** agents, run as a structured pipeline
- Narration is generated first, and its **measured audio duration** paces the animation
- The visual agent writes **Manim** code and **retries with the real render error** when a render fails
- Async job processing with SQLite job tracking, FFmpeg assembly, Docker setup
- Honest **Known Limitations** section in the repo

`LangGraph` `Groq` `Manim` `Piper TTS` `FFmpeg` `Flask` `Next.js` `SQLite` `Docker`

[Repository](https://github.com/heena-jindal/ai-study-video-generator) · [Live frontend](https://ai-study-video-generator.vercel.app/)

---

### 🤖 [AI Study Companion](https://github.com/heena-jindal/AI_study_Companion)
A backend-only study tool that covers the GenAI stack end to end: structured output, RAG, a tool-calling agent and evaluation.

- **RAG** over uploaded PDFs: chunking with overlap, local embeddings, ChromaDB, similarity-threshold filtering
- **LangGraph ReAct agent** that decides which tool to use, e.g. "quiz me on my weak topics"
- **Schema-enforced quizzes** via Groq Structured Outputs, plus SQLite weak-topic tracking
- **LLM-as-a-judge** faithfulness check to catch answers not grounded in the retrieved context

`LangGraph` `ChromaDB` `Sentence-Transformers` `Groq` `Pydantic` `Flask` `SQLite`

[Repository](https://github.com/heena-jindal/AI_study_Companion) · [Live API](https://ai-study-companion-m5qc.onrender.com) *(free tier, may be slow on first request)*

---

### 🚇 [MetroVerse](https://github.com/heena-jindal/MetroVerse)
An AI-powered Delhi Metro platform with route planning, ML-based crowd prediction, fare estimation, digital tickets, chatbot assistance and nearby attractions.

`Next.js` `Flask` `Python` `Machine Learning`

---

### 🌟 [VibeVerse](https://github.com/heena-jindal/VibeVerse)
An AI companion for introverted and socially anxious students: mood-aware chat, journaling, challenges and music/movie recommendations, with a crisis-safety branch that skips the AI and shows a helpline.

`Next.js` `Flask` `LangGraph` `Groq`

---

<details>
<summary><b>Earlier projects</b></summary>

<br>

- **[Smart College Assistant](https://github.com/heena-jindal/smart-college-assistant)**: academic resources, chatbot support, attendance management and leave applications (Next.js, TypeScript, Flask).
- **[Fake Certificate Detection](https://github.com/heena-jindal/fake-certificate-detection-ml)**: feature engineering and a Random Forest classifier to flag potentially fraudulent certificates.
- **[House Price Prediction](https://github.com/heena-jindal/house-price-prediction-linear-regression)**: linear regression on real housing data (scikit-learn).

</details>

---

## Tech stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-4B0082?style=flat-square)
![ChromaDB](https://img.shields.io/badge/ChromaDB-5A67D8?style=flat-square)
![Groq](https://img.shields.io/badge/Groq-000000?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## Currently

- Building an agentic AI system for air-quality hazard forecasting and personalized risk explanation (repo coming soon)
- Strengthening DSA: arrays, strings, trees, graphs, dynamic programming
- Learning AI evaluation and cloud deployment
