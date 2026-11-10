<!-- Header banner -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=180&section=header&text=Hi%2C%20I'm%20Vidhi%20👋&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Data%20Engineer%20in%20the%20making%20%7C%20Pipelines%20%E2%80%A2%20Warehouses%20%E2%80%A2%20Analytics&descAlignY=60&descSize=16" width="100%"/>
</p>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1000&color=2C9FAF&center=true&vCenter=true&width=600&lines=Building+Bronze+%E2%86%92+Silver+%E2%86%92+Gold+pipelines;Python+%7C+SQL+%7C+Airflow+%7C+dbt+%7C+Spark;Turning+raw+data+into+reliable+tables;Open+to+Junior+%2F+Associate+Data+Engineer+roles" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://veriperi.github.io/"><img src="https://img.shields.io/badge/Portfolio-veriperi.github.io-2C5364?style=for-the-badge&logo=githubpages&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/veriperi/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
</p>

---

## 🧭 About Me

```yaml
role:        Data Analyst & Digital Marketing Associate  (Jul 2023 – present, ~3 yrs)
targeting:   Data Engineer | Junior Data Engineer | Associate Data Engineer
focus:       batch pipelines, medallion architecture, data modelling, orchestration
education:   B.E. Information Technology, University of Mumbai (2023) — CGPA 8.7
currently:   building a Spark → S3 → Snowflake market-data pipeline 🚧
```

- 🛠️ I build end-to-end pipelines: **ingest → clean → model → serve**, with tests and orchestration in between
- 📊 Three years as an analyst means I design tables with the *people who query them* in mind
- 🐛 I like the debugging part: Docker volumes, SQLAlchemy sessions, and database locks have all taught me something
- 🌱 Learning right now: **Apache Spark, AWS (S3), Snowflake**

---

## 🚀 Featured Projects

### 🧠 [Content Intelligence Pipeline](https://github.com/veriperi/content-intelligence-pipeline) &nbsp;`⭐ featured`

> Ingests content from public APIs, enriches it with LLM-assisted categorisation and quality scoring, and models it into analytics-ready tables.

```mermaid
flowchart LR
    A[🌐 Public APIs] --> B[(🥉 Bronze<br/>raw)]
    B --> C[(🥈 Silver<br/>cleaned)]
    C --> D[🤖 LLM<br/>categorise + score]
    D --> E[(🥇 Gold<br/>dbt models)]
    F{{Apache Airflow}} -. orchestrates .-> B & C & E
```

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

**Engineering wins:** moved concurrent loading from SQLite to PostgreSQL to remove database-locking failures · fixed Docker volume persistence and SQLAlchemy session issues.

---

<table>
<tr>
<td width="50%" valign="top">

### 🌱 [WholeVegan Analytics](https://github.com/veriperi/wholevegan.co)
PostgreSQL analytical data layer on synthetic order data, served through an interactive Streamlit dashboard.

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

🔗 [**Live dashboard →**](https://wholevegan-analytics.streamlit.app)

</td>
<td width="50%" valign="top">

### 📈 [E-commerce KPI Dashboard](https://github.com/veriperi/ecommerce-kpi-dashboard)
KPI tracking for an e-commerce business: revenue, orders, conversion and customer metrics in one view.

![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### 📉 Nifty 50 Market Data Pipeline &nbsp;`🚧 in progress`
Minute-level Nifty 50 market data processed with Spark into an S3 data lake, warehoused in Snowflake, visualised in Tableau Public.

```
Kaggle (minute data) ──► Apache Spark ──► AWS S3 [Bronze → Silver → Gold] ──► Snowflake ──► Tableau Public
```

![Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS%20S3-569A31?style=flat-square&logo=amazons3&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)

</td>
</tr>
</table>

---

## 🧰 Tech Stack

| Area | Tools |
|---|---|
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white) |
| **Orchestration & Transformation** | ![Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white) ![dbt](https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white) ![Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white) |
| **Databases & Warehouses** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white) ![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white) |
| **Cloud & DevOps** | ![AWS](https://img.shields.io/badge/AWS%20S3-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white) |
| **Analysis & BI** | ![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white) ![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white) |

---

## 📊 GitHub Activity

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=veriperi&show_icons=true&hide_border=true&theme=tokyonight&count_private=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=veriperi&layout=compact&hide_border=true&theme=tokyonight&langs_count=6" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=veriperi&hide_border=true&theme=tokyonight" />
</p>

---

<p align="center">
  <i>“In God we trust. All others must bring data.”</i> — W. Edwards Deming
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=100&section=footer" width="100%"/>
