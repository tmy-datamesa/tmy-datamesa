# Hi there, I'm Tümay! 👋 

*I design AI systems by starting from the problem, not the model.*

I am an independent researcher, builder, and system designer. My background is not a straight line—it's an intersection. I hold an **MBA and an MSc in Construction Management**, and my career spans **civil engineering, financial risk analytics, underwriting, and applied AI**. 

I don't just write code; I design ecosystems. I focus on **agentic workflows, context engineering, and practical architecture decisions**, building products that are analytically sound and actually useful in the face of uncertainty. I partner with forward-thinking teams that value high-trust collaboration and continuous learning.

*Embrace AI’s potential, manage its risks carefully and remember the humans using it. ✨*

---

### 🧠 The Intersection (Business, People, and AI)

I believe that to understand AI, you first need to understand people, and then you need to understand money. I see AI systems as a continuation of human behavior and economic dynamics — not as isolated technical artifacts.

My approach to engineering is deeply holistic:

- **Product & Stakeholder Focus:** Having bridged the gap between lenders and investors, managed clients, and built cash flow scenarios, I build solutions that make business sense. I design for the end-user, not just the compiler.
- **Risk & Project Management:** My background in underwriting and construction management taught me how to navigate uncertainty, manage crises, and plan for the worst-case scenario. I apply this same rigor to AI system design.
- **Architecture follows need:** I build agentic workflows and routing systems not because they are trendy, but because complex problems require dynamic, context-aware solutions.
- **Evaluation is design, not an afterthought:** I treat evaluation as a fundamental part of the system architecture, ensuring faithfulness and relevance from day one.

### 🌍 Beyond Code

Technology doesn't exist in a vacuum. My interest in **psychology, neuroscience, philosophy, and history** deeply influences how I approach AI. I focus on building systems that respect human attention and augment reasoning rather than replace it.

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

### 🔬 Featured Products & Projects

### [kmk-deploy](https://github.com/tmy-datamesa/kmk-deploy) — Multi-Law Legal RAG Agent ⚖️
> AI legal assistant for Turkish condominium and neighborhood law. Agentic RAG architecture with 6 separate law sources.

- **The Challenge:** Turkish legal texts are highly structured but complex to navigate.
- **The Decision:** Instead of a massive single vector database, I implemented an **Agentic Router** that first decides *which* law to consult, mimicking how a real lawyer approaches a problem. This architectural choice improved faithfulness from 0.20 to 0.59.
- **Architecture:** Streamlit frontend → FastAPI backend on Cloud Run → GPT-4o with Function Calling → ChromaDB vector search across 6 law collections
- **Stack:** `Python` `OpenAI` `ChromaDB` `FastAPI` `Docker` `Cloud Run` `Streamlit` `MLflow` `RAGAS`
- **Live:** [Streamlit App](https://kmk-deploy-csnu3xbifrnaixgypfsa93.streamlit.app) | [API Docs](https://legal-rag-api-232706383774.europe-west1.run.app/docs)

---

### [yt-insight-hub](https://github.com/tmy-datamesa/yt-insight-hub) — YouTube Comment Analytics Pipeline 🎥
> End-to-end pipeline that turns YouTube comments into structured sentiment, topic, and aspect-level insights.

- **The Challenge:** Social media feedback is unstructured, noisy, and hard to quantify for product decisions.
- **The Decision:** Designed a 3-layer BigQuery schema (raw/core/ml) and used GPT-4o-mini to extract not just sentiment, but *strategic signals* (purchase intent, competitor comparison). This turns qualitative noise into quantitative BI metrics.
- **Pipeline:** YouTube API → BigQuery → LLM inference → Streamlit dashboard + Looker Studio
- **Stack:** `Python` `OpenAI` `BigQuery` `Streamlit` `Looker Studio` `YouTube API`
- **Live:** [Looker Dashboard](https://lookerstudio.google.com/s/gbf4u5q04WM)

---

### [Linkedin-Job-Tracker](https://github.com/tmy-datamesa/Linkedin-Job-Tracker) — AI-Powered Job Hunting Automation 🎯
> Pragmatic automation tool that scrapes LinkedIn listings, filters with GPT-4o-mini against custom CV criteria, and logs qualified matches to Google Sheets.

- **The Challenge:** Job hunting involves repetitive manual filtering of irrelevant listings.
- **The Decision:** Built a local automation script to solve a personal pain point. It demonstrates how to use AI practically for daily workflows, combining web scraping with LLM-based structured output filtering.
- **Stack:** `Python` `Playwright` `OpenAI API` `Google Sheets API`

---

### [steam-dataset-2025-insights](https://github.com/tmy-datamesa/steam-dataset-2025-insights) — Steam Market Analysis & Price Prediction 🎮
> Data-driven market analysis and price prediction for 240k+ Steam games. EDA, segmentation, and ML pipeline.

- **The Challenge:** Understanding pricing dynamics in a massive, highly skewed digital marketplace.
- **The Decision:** Applied rigorous exploratory data analysis before modeling. Used Prophet for time series forecasting and dbt for structured data transformation, treating data quality as the primary driver of model performance.
- **Stack:** `Python` `Pandas` `scikit-learn` `Prophet` `dbt` `Jupyter`

---

### [Data-Mesa-Focus](https://github.com/tmy-datamesa/Data-Mesa-Focus) — Focus Environment App 🌿
> Minimal focus environment designed around cognitive ergonomics.

- **The Philosophy:** "Flow — noise, slowly becoming rhythm. Ground — the mind, returning to itself. Space — thought, expanding into space." An exercise in cognitive ergonomics.
- **Stack:** `TypeScript` `Vercel`
- **Live:** [thinkslow.vercel.app](https://thinkslow.app/)

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=tmy-datamesa&show_icons=true&theme=transparent&hide_border=true&count_private=true&title_color=2f81f7&text_color=58a6ff&icon_color=2f81f7" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=tmy-datamesa&layout=compact&theme=transparent&hide_border=true&title_color=2f81f7&text_color=58a6ff" height="165" />
</p>
