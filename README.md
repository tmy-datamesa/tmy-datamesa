# Hi there, I'm Tümay! 👋 

Data scientist with a background in **engineering and finance**, interested in how **AI and data systems** can turn complex problems into practical solutions.
I enjoy building things that are both **analytically sound** and **actually useful** — from machine learning models to **LLM-powered tools** and **decision-support systems**.
Outside of code, I’m drawn to **history, philosophy, and anthropology** — fields that explore how humans think, evolve, and make sense of the world. 

*Embrace AI’s potential, manage its risks carefully and remember the humans using it. ✨*

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

- **Architecture:** Streamlit frontend → FastAPI backend on Cloud Run → GPT-4o with Function Calling → ChromaDB vector search across 6 law collections
- **Key decisions:** Agentic routing (LLM decides which law to query), chunking optimized for legal text structure (KISIM, BOLUM, Madde separators), microservice split for independent scaling
- **MLOps:** RAGAS evaluation (Faithfulness, Answer Relevancy) + MLflow experiment tracking
- **Stack:** `Python` `OpenAI` `ChromaDB` `FastAPI` `Docker` `Cloud Run` `Streamlit` `MLflow` `RAGAS`
- **Live:** [Streamlit App](https://kmk-deploy-csnu3xbifrnaixgypfsa93.streamlit.app) | [API Docs](https://legal-rag-api-232706383774.europe-west1.run.app/docs)

---

### [yt-insight-hub](https://github.com/tmy-datamesa/yt-insight-hub) — YouTube Comment Analytics Pipeline 🎥
> End-to-end pipeline that turns YouTube comments into structured sentiment, topic, and aspect-level insights.

- **Pipeline:** YouTube API → BigQuery (raw/core/ml layers) → LLM inference (GPT-4o-mini) → Streamlit dashboard + Looker Studio
- **NLP output per comment:** General sentiment, topic classification, aspect-based sentiment with evidence, strategic signals (purchase intent, competitor comparison, questions)
- **Data architecture:** 3-layer BigQuery schema (raw → curated → ml), ontology-driven topic/aspect taxonomy, reporting views for BI tools
- **Stack:** `Python` `OpenAI` `BigQuery` `Streamlit` `Looker Studio` `YouTube API`
- **Live:** [Looker Dashboard](https://lookerstudio.google.com/s/gbf4u5q04WM)

---

### [steam-dataset-2025-insights](https://github.com/tmy-datamesa/steam-dataset-2025-insights) — Steam Market Analysis & Price Prediction 🎮
> Data-driven market analysis and price prediction for 240k+ Steam games. EDA, segmentation, and ML pipeline.

- **Scope:** Exploratory data analysis on 240k+ games, customer segmentation, price prediction modeling, time series forecasting with Prophet
- **ML pipeline:** Feature engineering → model selection → evaluation, with dbt for data transformation
- **Stack:** `Python` `Pandas` `scikit-learn` `Prophet` `dbt` `Jupyter`

---

### [PowerBI-TheLook-ECommerce-Analysis](https://github.com/tmy-datamesa/PowerBI-TheLook-ECommerce-Analysis) — E-Commerce BI Dashboard
> Performance analytics dashboard for TheLook e-commerce dataset using Power BI and DAX.

- **Focus:** Revenue trends, product category performance, customer acquisition metrics, cohort analysis
- **Stack:** `Power BI` `DAX` `BigQuery`

---

### [Data-Mesa-Focus](https://github.com/tmy-datamesa/Data-Mesa-Focus) — Focus Environment App 🌿
> A minimal focus environment with music, night sky ambience, and reflective tools. Personal brand project.

- **Stack:** `TypeScript` `Vercel`
- **Live:** [thinkslow.vercel.app](https://thinkslow.vercel.app/)

---

### 🚀 What I'm Focused On
- **AI & LLM systems** – building practical applications with language models and retrieval systems  
- **Machine learning** – predictive models and data-driven analysis  
- **Data platforms & dashboards** – turning raw data into clear insights

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=tmy-datamesa&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=tmy-datamesa&layout=compact&theme=tokyonight&hide_border=true" height="165" />
</p>
