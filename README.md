# 👋 Hi, I'm Rodion Omelich

- 🎓 Third-year **Software Design with AI for Cloud Computing** student at TUS Athlone
- 🔬 Just finished an **ML internship at FlyRank AI** — search ranking over a 79M-row warehouse
- 📐 I care more about whether the evaluation is honest than about the model
- 🛠 Building end-to-end in **Python** and **Java** — from data to something that runs

---

### 🧰 Tech Stack

- **Languages** — Python, SQL, Java, HTML, CSS
- **ML** — scikit-learn, feature engineering, cross-validation
- **Data** — Pandas, NumPy, DuckDB, Hugging Face, Matplotlib, Seaborn
- **Concepts** — OOP, leakage-safe validation, Precision@K, agent-based modelling
- **Tools** — Git, Mesa / Solara, JUnit, Power BI, VS Code, PyCharm
- **Backend** — FastAPI, REST APIs, MongoDB Atlas, pytest, Docker
---

### 📌 Selected projects

**[Search Ranking & Discoverability](https://github.com/RodionOm/Search-ranking-ml)** — FlyRank AI ML internship (Jul–Sep 2026).
Which pages should a content reviewer look at first? On clients the model never saw (GroupKFold by client),
a logistic regression put **44 declining pages in its top 50 (Precision@50 0.88)** vs 0.80 for a rule baseline.
Found and documented a leakage trap (90-day totals contain the label window: AUC jumps from 0.680 to 0.909 with them).
Review queue with reason codes, a per-client cap and drift monitoring.

**[HomesAbove](https://github.com/Adwerse/HouseAbove)** — 🏆 one of 3 winning teams of 32 at Build for Ireland 2026
(OpenAI × Dogpatch Labs). Helps councils find vacant floors above shops. **My part:** the volunteer walk
pipeline (GPS/EXIF import, walk segmentation, idempotent MongoDB upserts, pHash de-duplication) and a
FastAPI badge engine with real-time SSE events (27 tests).

**[Airbnb Dublin — Market Analysis & Price Prediction](https://github.com/RodionOm/Airbnb_Dublin)**
Price model on 5,244 priced Dublin listings. XGBoost reached **R² 0.775 on log price, MAE €52**
against a 0.655 Ridge baseline; SHAP for the price drivers; VADER on 334k reviews. Known issues documented in the README.

**[AI Hiring Copilot](https://github.com/RodionOm/ai-hiring-copilot)**
Scores a CV against a job description: gpt-4o-mini returns structured JSON, Python validates it and
re-scores it by keyword coverage (0.75 LLM + 0.25 keywords). Streamlit UI, Docker, pytest, demo mode without an API key.

**[GaeligeWeb](https://github.com/RodionOm/GaeligeWeb)**
Chrome extension (Manifest V3) + Node server that turns any page into an Irish lesson:
summaries at three depths, word cards, a quiz. Built at an Irish-language hackathon at Dogpatch Labs, Dublin.

---

### 🚀 Currently
- Finishing the **search ranking capstone** paper
- Building a newspaper delivery system in **Java** with a team (OOP, JUnit, Scrum)
- Learning **Docker**

---

### 🌐 Connect
📧 bigirodion2005@gmail.com
💼 [LinkedIn](https://www.linkedin.com/in/rodion-omelich-bba55b378)
