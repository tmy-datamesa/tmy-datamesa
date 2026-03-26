# Hi there, I'm Tümay! 👋 

*I build intelligent systems by thinking slowly.*

My background spans **civil engineering, risk analytics, and applied AI**. I am interested in designing AI systems around real needs—especially **agentic workflows, context engineering, evaluation, and practical architecture decisions**. I focus on building things that are analytically sound and actually useful in the face of uncertainty.

*Embrace AI’s potential, manage its risks carefully and remember the humans using it. ✨*

---

### 🧠 How I Build (The Systems Mindset)

I don't just stack tools; I design systems. My approach to AI engineering is rooted in a few core principles:
- **Architecture follows need:** I build agentic workflows and routing systems not because they are trendy, but because complex problems require dynamic, context-aware solutions.
- **Evaluation is design, not an afterthought:** I treat evaluation (like RAGAS or MLflow tracking) as a fundamental part of the system architecture, ensuring faithfulness and relevance from day one.
- **Learning by shipping:** I believe in building to learn. I iterate through uncertainty, moving from basic prototypes to production-ready deployments, refining the context and structure at each step.

### 🌍 Beyond Code

Technology doesn't exist in a vacuum. My interest in **history, philosophy, and anthropology** deeply influences how I approach AI. When building systems like *Data Mesa*, I prioritize cognitive ergonomics—creating digital environments that respect human attention rather than exploiting it. I build tools that augment human reasoning, not replace it.

---

### 🛠️ Tech Stack & Focus 

| Area | Technologies |
|---|---|
| **Languages** | Python, SQL |
| **LLM / GenAI** | RAG, Agentic Workflows, LLM Evaluation, OpenAI API, Embeddings, Vector Databases (Chroma), Structured Output Design, Prompt Engineering |
| **ML / NLP** | scikit-learn, XGBoost, NLP, Transformers, Time Series Forecasting |
| **Analytics & BI** | BigQuery, Looker Studio, Power BI, EDA, Feature Engineering, Data Visualization |
| **Deployment & MLOps** | Docker, MLflow, Google Cloud Run, Vercel, Git, GitHub |
| **AI-Assisted Dev** | Cursor, Claude Code |

---

### 🔬 Featured Projects

### [kmk-deploy](https://github.com/tmy-datamesa/kmk-deploy) — Multi-Law Legal RAG Agent ⚖️
> AI legal assistant for Turkish condominium and neighborhood law. Agentic RAG architecture with 6 separate law sources.

- **The Challenge:** Turkish legal texts are highly structured but complex to navigate.
- **The Decision:** Instead of a massive single vector database, I implemented an **Agentic Router** that first decides *which* law to consult, mimicking how a real lawyer approaches a problem. This architectural choice improved faithfulness from 0.20 to 0.59.
- **Architecture:** Streamlit frontend → FastAPI backend on Cloud Run → GPT-4o with Function Calling → ChromaDB vector search across 6 law collections
- **Stack:** `Python` `OpenAI` `ChromaDB` `FastAPI` `Docker` `Cloud Run` `Streamlit` `MLflow` `RAGAS`
- **Live:** [Streamlit App](https://kmk-deploy-csnu3xbifrnaixgypfsa93.streamlit.app) | [API Docs](https://legal-rag-api-232706383774.europe-west1.run.app/docs)

---

### [Linkedin-Job-Tracker](https://github.com/tmy-datamesa/Linkedin-Job-Tracker) — AI-Powered Job Hunting Automation 🎯
> Pragmatic automation tool that scrapes LinkedIn listings, filters with GPT-4o-mini against custom CV criteria, and logs qualified matches to Google Sheets.

- **The Approach:** Built to solve a personal pain point. Demonstrates how to use AI practically for daily workflows, combining web scraping with LLM-based filtering.
- **Stack:** `Python` `Playwright` `OpenAI API` `Google Sheets API`

---

### [yt-insight-hub](https://github.com/tmy-datamesa/yt-insight-hub) — YouTube Comment Analytics Pipeline 🎥
> End-to-end pipeline that turns YouTube comments into structured sentiment, topic, and aspect-level insights.

- **Pipeline:** YouTube API → BigQuery (raw/core/ml layers) → LLM inference (GPT-4o-mini) → Streamlit dashboard + Looker Studio
- **NLP output per comment:** General sentiment, topic classification, aspect-based sentiment with evidence, strategic signals (purchase intent, competitor comparison, questions)
- **Stack:** `Python` `OpenAI` `BigQuery` `Streamlit` `Looker Studio` `YouTube API`
- **Live:** [Looker Dashboard](https://lookerstudio.google.com/s/gbf4u5q04WM)

---

### [steam-dataset-2025-insights](https://github.com/tmy-datamesa/steam-dataset-2025-insights) — Steam Market Analysis & Price Prediction 🎮
> Data-driven market analysis and price prediction for 240k+ Steam games. EDA, segmentation, and ML pipeline.

- **Scope:** Exploratory data analysis on 240k+ games, customer segmentation, price prediction modeling, time series forecasting with Prophet
- **Stack:** `Python` `Pandas` `scikit-learn` `Prophet` `dbt` `Jupyter`

---

### [Data-Mesa-Focus](https://github.com/tmy-datamesa/Data-Mesa-Focus) — Focus Environment App 🌿
> A minimal focus environment with music, night sky ambience, and reflective tools. Personal brand project.

- **Philosophy:** "Flow — noise, slowly becoming rhythm. Ground — the mind, returning to itself. Space — thought, expanding into space."
- **Stack:** `TypeScript` `Vercel`
- **Live:** [thinkslow.vercel.app](https://thinkslow.vercel.app/)

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=tmy-datamesa&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=tmy-datamesa&layout=compact&theme=tokyonight&hide_border=true" height="165" />
</p>
