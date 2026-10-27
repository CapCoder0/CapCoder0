<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Hey,%20I'm%20CapCoder0%20👋&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Software%20Engineer%20·%207%20years%20building%20systems%20that%20move%20data%20and%20make%20decisions&descSize=16&descAlignY=58" width="100%"/>

<a href="https://github.com/CapCoder0">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3500&pause=900&color=36BCF7&center=true&vCenter=true&width=640&lines=Real-time+streaming+pipelines+%E2%9A%A1;Production+ML+%26+MLOps+%F0%9F%A7%A0;Lakehouses+%26+analytics+engineering+%F0%9F%8F%9B%EF%B8%8F;Retrieval-augmented+AI+systems+%F0%9F%94%8E;APIs+that+hold+up+under+load+%F0%9F%9A%80" alt="Typing intro"/>
</a>

<br/>

![Profile views](https://komarev.com/ghpvc/?username=CapCoder0&color=36BCF7&style=flat-square&label=Profile+views)
![Experience](https://img.shields.io/badge/Experience-7%2B%20years-2c5364?style=flat-square)
![Focus](https://img.shields.io/badge/Focus-Data%20·%20ML%20·%20Backend-203a43?style=flat-square)

</div>

---

### 🧑‍💻 About me

I'm a software engineer with **7 years of experience** building backend and data systems: services that ingest events in real time, turn them into features, and serve decisions in milliseconds.

My work sits where **software engineering, data engineering and machine learning** meet:

- ⚡ **Streaming systems.** Kafka and Spark Structured Streaming pipelines with event-time windows, watermarks and idempotent writes
- 🧠 **ML in production.** Feature stores, model registries, champion/challenger A/B tests, drift detection and automatic rollback
- 🏛️ **Data platforms.** Medallion lakehouses, dbt models, Snowflake and Databricks, with a validation gate at every layer
- 🔎 **Applied AI.** Retrieval pipelines with hybrid search, cross-encoder reranking and multimodal document parsing
- 🚀 **Shipping it.** Docker, Kubernetes/Helm, CI/CD, Prometheus/Grafana, and load tests before launch

```python
class CapCoder0:
    role       = "Software Engineer"
    experience = "7+ years"
    focus      = ["Backend", "Data Engineering", "ML Systems", "Applied AI"]
    principles = [
        "Measure before you optimize",
        "Validate data at every boundary",
        "Make failures loud and rollbacks boring",
        "Write the README you wish you'd found",
    ]
```

---

### 🌟 Featured projects

<table>
<tr>
<td width="50%" valign="top">

#### 🛡️ [Fraud Guard](https://github.com/CapCoder0/Fraud-Guard)
Real-time payment fraud detection built as a full ML platform. Kafka → Spark → feature store → XGBoost behind FastAPI, plus a model registry, A/B routing, Evidently drift detection with auto-rollback, and Helm for Kubernetes.

**166k requests · 0 failures · 110 ms median** under load

![](https://img.shields.io/badge/-Kafka-231F20?logo=apachekafka&logoColor=white&style=flat-square)
![](https://img.shields.io/badge/-Spark-E25A1C?logo=apachespark&logoColor=white&style=flat-square)
![](https://img.shields.io/badge/-XGBoost-1E88E5?style=flat-square)
![](https://img.shields.io/badge/-FastAPI-009688?logo=fastapi&logoColor=white&style=flat-square)
![](https://img.shields.io/badge/-Kubernetes-326CE5?logo=kubernetes&logoColor=white&style=flat-square)

</td>
<td width="50%" valign="top">

#### 🏥 [Healthcare Claims & EHR Lakehouse](https://github.com/CapCoder0/healthcare-claims-ehr-lakehouse)
A Bronze → Silver → Gold lakehouse that links clinical records and Medicare-style claims into a **Patient 360** view, feeding dbt, Snowflake, Databricks Delta, a PyTorch risk model, Streamlit and a live Tableau dashboard.

**250 patients × 71 features · validation gate at every layer**

![](https://img.shields.io/badge/-dbt-FF694B?logo=dbt&logoColor=white&style=flat-square)
![](https://img.shields.io/badge/-Snowflake-29B5E8?logo=snowflake&logoColor=white&style=flat-square)
![](https://img.shields.io/badge/-Databricks-FF3621?logo=databricks&logoColor=white&style=flat-square)
![](https://img.shields.io/badge/-Prefect-024DFD?logo=prefect&logoColor=white&style=flat-square)
![](https://img.shields.io/badge/-PyTorch-EE4C2C?logo=pytorch&logoColor=white&style=flat-square)

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🛒 [Real-time Retail Pipeline](https://github.com/CapCoder0/realtime-retail-pipeline)
Every sale streamed, aggregated and analyzed within seconds. Spark windows feed a PostgreSQL star schema, an ML service runs RFM segmentation, K-Means and Apriori basket rules, and a live Streamlit dashboard shows the results. Seven containers, one `docker compose up`.

![](https://img.shields.io/badge/-Kafka-231F20?logo=apachekafka&logoColor=white&style=flat-square)
![](https://img.shields.io/badge/-PostgreSQL-4169E1?logo=postgresql&logoColor=white&style=flat-square)
![](https://img.shields.io/badge/-scikit--learn-F7931E?logo=scikitlearn&logoColor=white&style=flat-square)
![](https://img.shields.io/badge/-Streamlit-FF4B4B?logo=streamlit&logoColor=white&style=flat-square)
![](https://img.shields.io/badge/-Docker-2496ED?logo=docker&logoColor=white&style=flat-square)

</td>
<td width="50%" valign="top">

#### 🎓 [Tutor RAG](https://github.com/CapCoder0/tutor-rag)
A retrieval engine for lecture slides. It reads PDFs and PowerPoints (diagrams too, via Tesseract and Florence-2), chunks them by slide, and answers questions with adaptive BM25 + dense search, cross-encoder reranking and MMR.

**5-stage retrieval · query-aware fusion**

![](https://img.shields.io/badge/-Hugging%20Face-FFD21E?logo=huggingface&logoColor=black&style=flat-square)
![](https://img.shields.io/badge/-ChromaDB-FF6B35?style=flat-square)
![](https://img.shields.io/badge/-PyTorch-EE4C2C?logo=pytorch&logoColor=white&style=flat-square)
![](https://img.shields.io/badge/-FastAPI-009688?logo=fastapi&logoColor=white&style=flat-square)

</td>
</tr>
</table>

---

### 🧰 Tech stack

<div align="center">

**Languages & backend**

<img src="https://skillicons.dev/icons?i=python,bash,fastapi,postgres,redis&perline=8" />

**Data & streaming**

<img src="https://skillicons.dev/icons?i=kafka&perline=8" />
<br/>
<img src="https://img.shields.io/badge/Apache%20Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white"/>
<img src="https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white"/>
<img src="https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white"/>
<img src="https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white"/>
<img src="https://img.shields.io/badge/DuckDB-FFF000?style=for-the-badge&logo=duckdb&logoColor=black"/>
<img src="https://img.shields.io/badge/Prefect-024DFD?style=for-the-badge&logo=prefect&logoColor=white"/>

**Machine learning & AI**

<img src="https://skillicons.dev/icons?i=pytorch,sklearn&perline=8" />
<br/>
<img src="https://img.shields.io/badge/XGBoost-1E88E5?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"/>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white"/>
<img src="https://img.shields.io/badge/Evidently-ED0A3F?style=for-the-badge"/>
<img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>

**Cloud, DevOps & observability**

<img src="https://skillicons.dev/icons?i=aws,docker,kubernetes,githubactions,prometheus,grafana,linux,git&perline=8" />

**Visualization**

<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white"/>
<img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white"/>
<img src="https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white"/>

</div>

---

### 📊 GitHub stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=CapCoder0&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=CapCoder0&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" />

<img src="https://streak-stats.demolab.com?user=CapCoder0&theme=tokyonight&hide_border=true" />

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=CapCoder0&theme=tokyo-night&hide_border=true&area=true" />

</div>

---

### 🤝 Let's talk

I'm happy to chat about **streaming architectures, ML platforms, data quality, or retrieval systems**, or about a role where these come together.

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-CapCoder0-181717?style=for-the-badge&logo=github)](https://github.com/CapCoder0)

<sub>⭐ If a project here helps you, a star is always appreciated.</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=110&section=footer" width="100%"/>

</div>
