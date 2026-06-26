<!-- ═══════════════════════════════════════════════════════════════
     PUNITH V — GitHub Profile README
     Repo: github.com/PUNITH-V/PUNITH-V  (same name as username)
     ═══════════════════════════════════════════════════════════════ -->

<div align="center">

<!-- Typing SVG — the single animated headline -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1000&color=C3FF00&center=true&vCenter=true&width=600&lines=Agentic+AI+Engineer;RAG+%7C+LLMs+%7C+Production+Systems;I+build+AI+that+ships%2C+not+just+demos.)](https://git.io/typing-svg)

</div>

---

### `whoami`

```python
punith = {
    "role"      : "Agentic AI Engineer — Final Year B.Tech CS (AI & ML)",
    "university": "Woxsen University, Hyderabad  ·  CGPA 8.68",
    "focus"     : ["RAG Pipelines", "LLM Orchestration", "Production Deployment"],
    "shipped"   : 3,   # production-deployed AI systems
    "available" : "July 2026",
    "location"  : "Hyderabad, India",
}
```

> I don't build toy demos. I scope a problem, pick an architecture, ship it, then measure it.

---

### 🚀 Production Systems

| System | What it solves | Stack | Metrics |
|--------|---------------|-------|---------|
| **[DocQuery](https://docquery-rag-powered-multi-document-search.streamlit.app)** | Natural-language search across 100+ page PDFs with exact source citations | LangChain · ChromaDB · BM25 · HuggingFace · Groq · Streamlit | 922 chunks → top-5 via RRF + cross-encoder · 2.3s avg latency · 50+ real queries |
| **[YouTube Summarizer v2](#)** | Makes hour-long videos digestible beyond LLM context limits | LangChain · Groq (Llama3) · youtube-transcript-api · Streamlit | 3,357 → 1,021 words · **69.7% compression** · 3-case graceful degradation |
| **[Prompt Lab](#)** | Objective comparison of zero-shot / few-shot / CoT with LLM-as-judge scoring | FastAPI · React · LangChain · Groq · PostgreSQL · Render · Vercel | Token-streaming · 3 eval dimensions · full-stack deployed |

---

### 🛠 Tech Stack

**Agentic AI & LLMs**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-FF6B35?style=flat-square&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Claude](https://img.shields.io/badge/Claude_API-CC785C?style=flat-square&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

**Backend & APIs**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

**Frontend & Deployment**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

**Data & ML**

![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B35?style=flat-square&logoColor=white)

---

### 📊 GitHub Stats

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=PUNITH-V&show_icons=true&theme=chartreuse-dark&hide_border=true&bg_color=0a0a0f&title_color=c3ff00&icon_color=c3ff00&text_color=e8e8f0&ring_color=7c5cfc" />
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=PUNITH-V&layout=compact&theme=chartreuse-dark&hide_border=true&bg_color=0a0a0f&title_color=c3ff00&text_color=e8e8f0&langs_count=6" />

</div>

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=PUNITH-V&theme=dark&hide_border=true&background=0a0a0f&ring=C3FF00&fire=7c5cfc&currStreakLabel=C3FF00&sideLabels=6b6b82&dates=6b6b82)](https://git.io/streak-stats)

</div>

---

### 🧠 How I approach systems

```
Query arrives
    │
    ▼
[BM25 keyword search] ──┐
                         ├──► Reciprocal Rank Fusion ──► Cross-encoder rerank ──► LLM ──► Cited answer
[Semantic vector search]─┘
    │
    └──► Eval pipeline: source diversity · citation presence · answer quality
```

> Every system I ship has an **evaluation loop** — because "it works" isn't a metric.

---

### 💼 Experience

**AI Research Intern** — Woxsen University AI Research Centre *(Jan – Jul 2025)*
- Built Speech-to-Text pipeline with OpenAI Whisper · **85% accuracy** on diverse Indian accents
- Transformer-based summarization: 30-min video reviews → 2-min readable summaries

**ML Trainee** — Infosys Springboard *(Dec 2025 – Feb 2026)*
- LSTM + Random Forest for energy consumption forecasting
- Flask dashboard for real-time prediction with pipeline docs and eval reports

---

### 🏅 Certifications

![Oracle GenAI](https://img.shields.io/badge/Oracle_OCI-Generative_AI_Professional_2025-F80000?style=flat-square&logo=oracle&logoColor=white)
![Oracle DS](https://img.shields.io/badge/Oracle_OCI-Data_Science_Professional_2025-F80000?style=flat-square&logo=oracle&logoColor=white)

---

### 📬 Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-punith--v1-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/punith-v1)
[![Email](https://img.shields.io/badge/Email-punithvuppu@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:punithvuppu@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-Live-C3FF00?style=flat-square&logoColor=black)](https://docquery-rag-powered-multi-document-search.streamlit.app)
[![DocQuery](https://img.shields.io/badge/DocQuery-Live_Demo-7c5cfc?style=flat-square&logoColor=white)](https://docquery-rag-powered-multi-document-search.streamlit.app)

</div>

---

<div align="center">
<sub>Available for AI internships from <strong>July 2026</strong> · Hyderabad, India</sub>
</div>
