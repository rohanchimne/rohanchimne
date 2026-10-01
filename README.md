<p align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0f2027,50:203a43,100:2c5364&height=180&section=header&text=Rohan%20Chimne&fontSize=45&fontColor=ffffff&fontAlignY=40&desc=Data%20Engineer%20%7C%20Lakehouse%20Migrations%20%7C%20Data%20Quality&descSize=18&descAlignY=68"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?size=24&duration=3000&color=36BCF7&center=true&vCenter=true&width=900&lines=Data+Engineer+%40+Sterlite+Technologies+(STL);Ex-Uber+Ads+Data+Analyst+(via+Nineleaps);Multi-TB+BigQuery+%E2%86%92+Databricks+Migration+%7C+600%2B+Tables;I+own+whether+the+data+is+right" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/rohanchimne"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:rohan.chimne@utexas.edu"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <img src="https://img.shields.io/badge/Austin,_TX-2c5364?style=for-the-badge&logo=googlemaps&logoColor=white"/>
  <img src="https://img.shields.io/badge/Open_to-Data_%26_Analytics_Engineering_roles-36BCF7?style=for-the-badge"/>
</p>

---

## ⚡ TL;DR (30 seconds)

* 🎓 **MS Business Analytics, UT Austin** (May 2026) · B.Tech Electrical Engineering
* 🏭 **Now:** Data Engineer, AI & Analytics @ **STL**, migrating a **multi-TB, 600+ table BigQuery estate to Databricks**
* 🚗 **Before:** Data Analyst on **Uber Ads** (via Nineleaps) · Cloud Data Engineer on a **MySQL → Snowflake migration on AWS**
* 🧭 **Through-line:** two production migrations, three jobs, one theme: **validation, reconciliation and parity gates that stop bad numbers before anyone sees them**

---

## 📊 Impact at a Glance

| | Result | Where |
|:-:|---|---|
| 🛡️ | **2 production-bound defects caught before release**, incl. a timezone shift distorting daily revenue by **2%** | STL |
| 🔐 | Verified multi-TB datasets **across two clouds without moving data**, Tier-1 parity run in **~20 min** | STL |
| ⏱️ | **~15 hrs/week** of manual quality reporting eliminated with a self-serve Streamlit app | STL |
| 🚨 | Stopped a **4% ad-spend under-report** from reaching **20+ stakeholders** | Uber Ads |
| 📐 | One SQL source-of-truth for reach, CTR & conversion across **6 ad-product verticals** | Uber Ads |
| 🤝 | Delivered attribution feeds behind a **multi-million-dollar Unilever Joint Business Plan** | Uber Ads |
| 💰 | **30% cut** in both manual effort and compute cost on a Snowflake migration | Grace Infosoft |

---

## 💼 Experience

**🏭 Sterlite Technologies (STL)** · Data Engineer, AI & Analytics · *Jul 2026 – Present*
* Designed the **parity framework that gates every dataset's cutover** in a 600+ table BigQuery → Databricks migration: source-side aggregation pushdown + **SHA-256 row fingerprinting**, config-as-code in Git
* Sequenced migration waves for **23 Tier-1 datasets** from a dependency graph built on **Unity Catalog lineage** + BigQuery `INFORMATION_SCHEMA`; built **silver/gold Spark pipelines** for 2 domains
* Built **5 Lakeflow pipelines** delivering SAP-sourced supply-chain data (UoM normalization, lead-time derivation) to an external planning partner (Kinaxis) on their integration spec

**🚗 Nineleaps (client: Uber Ads)** · Data Analyst · *Sep 2023 – Jun 2025*
* Standardized ad KPIs into a reusable **SQL metric layer on Presto over Hive**, resolving a served-vs-viewable impression dispute across Rides and Eats
* Added **reconciliation + freshness checks** so every expected partition exists before any report runs
* Automated **Python + SQL** reporting pipelines, saving **~10 hrs/week**

**☁️ Grace Infosoft** · Cloud Data Engineer (Trainee) · *Jun 2022 – Sep 2023*
* Engineered the **AWS transformation layer** (Glue on S3, Lambda event triggers) for a legacy **MySQL → Snowflake** migration

---

## 🏗️ Featured Projects

### 🤖 NYC Airbnb Market Intelligence Platform · *Snowflake · Cortex AI · Streamlit*
* End-to-end Snowflake platform on **102,600 listings**: Bronze → Silver → Gold, **star schema** (1 fact, 4 dims), **MERGE-based incremental loads**
* GenAI layer with **Snowflake Cortex**: sentiment, summarization, LLM price-tier classification, semantic search, and **natural language → SQL** (Cortex Analyst)

### 🚀 Airbnb ELT Pipeline · *dbt · Databricks · GitHub Actions*
* Medallion architecture with **SCD Type 2** and incremental models
* Custom **dbt tests** + **CI on GitHub Actions**; analyzed seasonality, pricing dispersion and host behavior

### 🧠 Fraud Detection ML Benchmark · *Python · Scikit-learn · Qiskit* · MSBA Capstone sponsored by TransUnion
* Random Forest vs. SVM vs. **Quantum SVM** on identical stratified splits and PCA features (ROC-AUC, PR-AUC, calibration)
* Finding: **well-tuned classical models beat the quantum approach** on production-relevant metrics

---

## 🧩 Tech Stack

<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="35" title="Python"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" height="35" title="MySQL"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" height="35" title="AWS"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/googlecloud/googlecloud-original.svg" height="35" title="GCP"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" height="35" title="Docker"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" height="35" title="Git"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Databricks-FF3621?style=flat&logo=databricks&logoColor=white"/>
  <img src="https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat&logo=apachespark&logoColor=white"/>
  <img src="https://img.shields.io/badge/Snowflake-29B5E8?style=flat&logo=snowflake&logoColor=white"/>
  <img src="https://img.shields.io/badge/BigQuery-669DF6?style=flat&logo=googlebigquery&logoColor=white"/>
  <img src="https://img.shields.io/badge/dbt-FF694B?style=flat&logo=dbt&logoColor=white"/>
  <img src="https://img.shields.io/badge/Presto-5890FF?style=flat&logo=presto&logoColor=white"/>
  <img src="https://img.shields.io/badge/Hive-FDEE21?style=flat&logo=apachehive&logoColor=black"/>
  <img src="https://img.shields.io/badge/AWS_Glue_%7C_S3_%7C_Lambda-232F3E?style=flat&logo=amazonwebservices&logoColor=white"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/SQL-336791?style=flat&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/PySpark-E25A1C?style=flat&logo=apachespark&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white"/>
  <img src="https://img.shields.io/badge/Tableau-E97627?style=flat&logo=tableau&logoColor=white"/>
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=flat&logo=powerbi&logoColor=black"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white"/>
</p>

**Core:** Lakehouse migrations · Medallion architecture · Dimensional modeling · Parity & reconciliation testing · Data-quality expectations · Unity Catalog governance

---

## 🧠 AI + Data

* **Natural language → SQL** shipped with Snowflake Cortex Analyst over a governed semantic view
* Draft pipelines with **Databricks Genie**, then hand-correct business logic, data-quality checks and schema
* Prototyping **agentic AI workflows** to automate recurring pipeline operations at STL

---

<p align="center">
  <i>Building data systems people can trust: if the number is wrong, nothing downstream matters.</i>
</p>
