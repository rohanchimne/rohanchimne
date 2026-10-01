<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/hero-dark.svg">
  <img alt="Rohan Chimne, Data Engineer at STL, formerly Uber Ads analytics. I build lakehouse pipelines and the validation that proves the numbers are right before anyone sees them." src="assets/hero-light.svg" width="100%">
</picture>

<p align="center">
  <a href="https://www.linkedin.com/in/rohanchimne"><b>LinkedIn</b></a> &nbsp;|&nbsp;
  <a href="mailto:rohan.chimne@utexas.edu"><b>rohan.chimne@utexas.edu</b></a> &nbsp;|&nbsp;
  Open to Data Engineering and Analytics Engineering roles
</p>

Two production migrations, three jobs, one through-line: I own whether the data is right. At **STL** I'm moving a multi-TB, 600+ table BigQuery estate onto Databricks and wrote the parity gate every dataset must pass before cutover. At **Uber Ads** I built the SQL metric layer and the reconciliation checks that kept wrong numbers away from 20+ stakeholders.

## Impact

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/impact-dark.svg">
  <img alt="600+ tables migrated and gated by parity checks; 2 production-bound defects stopped, including a 2% revenue shift; ~15 hrs/week of manual reporting replaced; 4% ad-spend under-report caught before reaching 20+ stakeholders; 6 ad verticals unified on one SQL source of truth; 30% less effort and compute on a MySQL to Snowflake migration." src="assets/impact-light.svg" width="100%">
</picture>

## Career

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/timeline-dark.svg">
  <img alt="Career timeline: Cloud Data Engineer at Grace Infosoft (2022 to 2023), Data Analyst on Uber Ads via Nineleaps (2023 to 2025), MS Business Analytics at UT Austin (2026), Data Engineer at STL (2026 to now)." src="assets/timeline-light.svg" width="100%">
</picture>

## How I gate a migration

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/parity-dark.svg">
  <img alt="Parity framework: BigQuery and Databricks each aggregate in place and produce SHA-256 row fingerprints under canonical formatting rules; results are compared using config-as-code from Git; passing datasets cut over, failing ones raise an exception." src="assets/parity-light.svg" width="100%">
</picture>

The framework I designed at STL. Each engine aggregates and fingerprints its own rows, so multi-TB tables are verified across two clouds without copying data. Migration waves for 23 Tier-1 datasets were sequenced from a dependency graph built on Unity Catalog lineage and BigQuery `INFORMATION_SCHEMA`.

## Selected projects

| Project | What it proves | Stack |
|---|---|---|
| **NYC Airbnb Market Intelligence Platform** | End-to-end warehouse on 102,600 listings: medallion layers, star schema (1 fact, 4 dims), MERGE-based incremental loads, plus a natural-language-to-SQL interface and LLM classification with Snowflake Cortex | Snowflake, SQL, Cortex AI, Streamlit |
| **Airbnb ELT Pipeline** | Bronze, silver and gold layers with SCD Type 2 and incremental models, custom dbt tests and CI on every push | dbt, Databricks, GitHub Actions |
| **Fraud Detection ML Benchmark** <br><sub>MSBA capstone sponsored by TransUnion</sub> | Random Forest, SVM and quantum SVM on identical stratified splits and PCA features; well-tuned classical models won on ROC-AUC, PR-AUC and calibration | Python, scikit-learn, Qiskit |

## Stack

| Layer | Tools |
|---|---|
| Lakehouse and warehouse | Databricks (Delta Lake, Unity Catalog, Metric Views, Lakeflow, Workflows), Snowflake, BigQuery |
| Processing | SQL, Python, PySpark, Spark, Presto, Hive |
| Cloud | AWS (Glue, S3, Lambda), GCP |
| Quality and modeling | Parity and reconciliation testing, freshness checks, medallion architecture, star schema, dbt |
| Delivery | Git, config-as-code, GitHub Actions, Docker, Streamlit, Tableau, Power BI |
| AI | Databricks Genie and AI/BI, Snowflake Cortex (natural language to SQL, LLM classification) |
