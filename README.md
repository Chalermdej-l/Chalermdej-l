# Chalermdej Lematavekul

**Data Engineer / Data Platform Engineer** · Bangkok, Thailand

I build production data platforms — event tracking, batch and event-driven pipelines, workflow orchestration, and the analytics layers on top. Currently a Generative AI Engineer at Xponential, where most of my work is data platform engineering: Snowplow event pipelines, Airflow on Kubernetes, dbt models, and BigQuery cost and governance.

Open to **Data Engineering / Data Platform Engineering** roles with more ownership of production systems.

[Portfolio](https://chalermdej-l.github.io/Portfolio/) · [LinkedIn](https://www.linkedin.com/in/chalermdej-l/) · [Email](mailto:chalermdej.lematavekul@gmail.com)

---

## What I work on

**Xponential** — Generative AI Engineer · Apr 2024 – Present
Data platform work for a large-scale super app.
- Led migration of super-app event tracking from Adobe Analytics to **Snowplow** — event schemas, data contracts, testing, rollout, cross-team coordination.
- Led the initial setup of **Airflow 3 on Kubernetes** (Helm), with parameterized backfills, manual reruns, and Slack failure alerts.
- Built **dbt** staging/mart/reporting layers; cut BigQuery cost and runtime via partitioning, clustering, and required filters.
- Implemented **PII masking and fine-grained access controls** in BigQuery for data governance.
- Built **Pub/Sub** Python workers routing Snowplow events to third parties (AppsFlyer).
- Daily customer-attribute pipelines processing **~100K–1M+ records per run**.
- **Gemini-based OCR** worker for receipt classification and structured extraction.
- Maintained **Weaviate** and ingestion pipelines backing RAG chatbot applications.
- Docker, Terraform, HashiCorp Vault for secrets.

**Avalon Analytics** — Senior Data Analyst · Oct 2022 – Apr 2024 · Data Analyst · Feb 2022 – Sep 2022
Pipelines, automation and integrations for hospitality analytics.
- Python interface automation for the Opera PMS — **cut >30 min per interface** and removed manual error.
- Fixed daily reporting delays with a Python solution **saving >45 working hours/month**.
- Built Opera Cloud API and RapidAPI ingestion pipelines into SQL Server; automated reconciliation scripts; SSIS packages; Power BI dashboards and DAX models.

*Earlier: Tax Specialist at Traveloka, Accounting Officer — an accounting background that still pays off in reconciliation, controls, and data accuracy.*

---

## Tech Stack

**Languages** · Python · SQL · Bash
**Data & Orchestration** · Airflow · dbt · Snowplow · Prefect · Pub/Sub · BigQuery · SQL Server · SSIS
**Cloud & Infra** · GCP · AWS · Azure · Docker · Kubernetes · Terraform · Helm · Vault
**AI & ML** · Gemini · Weaviate · RAG pipelines · MLflow · XGBoost · scikit-learn · TensorFlow
**Engineering practice** · pytest · ruff · pre-commit · GitHub Actions · Make
**BI** · Power BI · Looker Studio

---

## Selected Projects

Self-directed projects covering the ML and AI side of my work — model training, deployment, monitoring, and the infrastructure around them, each built and deployed end-to-end.

Every repo below is treated like production code: a pytest suite that runs without cloud credentials, ruff formatting and linting, pre-commit hooks, Terraform validation, and a GitHub Actions pipeline running all of it on each push.

**[FRED Economic Data Pipeline](https://github.com/Chalermdej-l/Final_Project_FredETE)** — Monthly ELT over the St. Louis Fed API into BigQuery, surfaced in Looker Studio.
`Python` · `Prefect` · `dbt` · `Terraform` · `GCS` · `BigQuery`

**[MLOps Pipeline](https://github.com/Chalermdej-l/Mlop_Project)** — End-to-end XGBoost training and serving with experiment tracking, model registry, and drift monitoring.
`Python` · `XGBoost` · `MLflow` · `Prefect` · `Evidently` · `Grafana` · `AWS`

**[Flight Time Prediction](https://github.com/Chalermdej-l/Flight_Prediction_Project)** — Event-driven flight-duration scoring through Event Hubs with a scikit-learn model.
`Python` · `scikit-learn` · `Azure Event Hubs` · `Docker` · `Terraform`

**[LLM Stock Analysis](https://github.com/Chalermdej-l/LLM_Stock_Analysis)** — Multi-source equity screener (SEC 13F, Dataroma, Finviz) with an LLM chat layer over Cloud SQL.
`Python` · `Groq/Llama` · `Chainlit` · `Postgres` · `Terraform` · `GCP`

**[Realtime Emotion Detection](https://github.com/Chalermdej-l/Realtime_Emotion_Detector)** — Webcam emotion classification, trained end-to-end and deployed as a serverless inference endpoint.
`Python` · `TensorFlow` · `OpenCV` · `Azure Functions` · `Docker` · `Terraform`

**[Booking.com Hotel Scraper](https://github.com/Chalermdej-l/Portfolio-Project-Web_Scraping)** — Sitemap-driven scraping pipeline with sharded parallel workers, de-duplication, and bulk load into SQL Server.
`Python` · `BeautifulSoup` · `pandas` · `SQL Server` · `pytest`

---

## Certifications

- [Microsoft Certified: Azure Data Engineer Associate](https://drive.google.com/file/d/189F-eZZr0E3epHJ7QTup3WVelz8lklQZ/view?usp=sharing)
- [Microsoft Certified: Azure Data Analyst Associate](https://drive.google.com/file/d/17EXqy2GkYpFT-5ZcuxvRr01Lt2HX-c0F/view?usp=sharing)
- [Data Engineering Zoomcamp](https://drive.google.com/file/d/1mDXsp89leCp-S2dqtvtvfruZPggFlPn7/view?usp=sharing) — DataTalks.Club
- [MLOps Zoomcamp](https://drive.google.com/file/d/11UzSXJGMqmRQiQosy2Q785lYkpqPRWCR/view?usp=sharing) — DataTalks.Club

<details>
<summary>More certifications</summary>

- [Machine Learning Zoomcamp](https://drive.google.com/file/d/124L7YMODfAspdm-hu0dL-3WqBe5oxjhy/view?usp=sharing) — DataTalks.Club
- [Microsoft Certified: Security, Compliance and Identity Fundamentals (SC-900)](https://drive.google.com/file/d/157i3V-5jRZlvqzARS2YB7nflgt49oMoF/view?usp=sharing)
- [Microsoft Certified: Azure Data Fundamentals (DP-900)](https://drive.google.com/file/d/1ZO7_quTkeR36v_64v3F01Q65abmRs9mh/view?usp=sharing)
- [Microsoft Certified: Azure Fundamentals (AZ-900)](https://drive.google.com/file/d/1J0ByS2T7RUMxx4VlfdxuHuDx6UAqSrFA/view?usp=sharing)
- [Python Data Analysis](https://drive.google.com/file/d/1ztHPz45LApoW95NRMkeJ3o--JhC3rBoJ/view?usp=sharing) — LinkedIn Learning
- [Python Data Structures and Algorithms](https://drive.google.com/file/d/1W8qDbcar-t9eH7LvMwage5kaSqs312as/view?usp=sharing) — LinkedIn Learning

</details>

---

## GitHub

![GitHub stats](https://github-readme-stats.vercel.app/api?username=chalermdej-l&rank_icon=github&theme=vue&line_height=20&card_width=450)

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Chalermdej-l/Chalermdej-l/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Chalermdej-l/Chalermdej-l/output/github-contribution-grid-snake.svg">
  <img alt="GitHub contribution grid snake animation" src="https://raw.githubusercontent.com/Chalermdej-l/Chalermdej-l/output/github-contribution-grid-snake.svg">
</picture>

---

## Contact

- **Email** — [chalermdej.lematavekul@gmail.com](mailto:chalermdej.lematavekul@gmail.com)
- **LinkedIn** — [chalermdej-l](https://www.linkedin.com/in/chalermdej-l/)
- **Portfolio** — [chalermdej-l.github.io/Portfolio](https://chalermdej-l.github.io/Portfolio/)

Languages: Thai (native) · English (professional working)
