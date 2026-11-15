# Basit ur Rehman
**Data & Analytics Engineering Intern (*Stage de fin d'études* · 6 Months · Feb/Mar 2027) | Python · SQL · dbt · Apache Airflow · Docker**  
Paris Region, France (Île-de-France) | [Portfolio](https://basitrehmankhattak.github.io/BasiturRehmanPortfolio/) | [LinkedIn](https://www.linkedin.com/in/basit-ur-rehman/) | basitrehman97@gmail.com

## About Me
I am a Master's student in Paris pursuing an **M2 in Intelligent Systems & Computer Vision (SIVO)** at **Université Sorbonne Paris Nord**, following an **M1 in Data Science & AI** at **EPITA Paris**.

Before my Master's in France, I spent **3+ years running production infrastructure** at **u-blox** (Switzerland) and **NGT Sol**, where I built my foundation in system reliability, observability, and automation. Today, I apply that same production mindset to **Data & Analytics Engineering**—designing **ETL/ELT pipelines**, **dimensional data models**, and **data quality checks** that are tested, observable, and easy to operate.

- **Target:** Seeking a **6-month End-of-Studies Internship (*stage de fin d'études*) starting February/March 2027** (*convention de stage* provided) in **Data Engineering**, **Analytics Engineering**, or **Data Platform Engineering** in Île-de-France.
- **Languages:** English (Fluent / C1) · French (Intermediate / B1 — comfortable in bilingual teams) · Urdu / Hindi (Native).

## Featured Projects

### 1. [Automated Weather ELT & Observability Pipeline](https://github.com/Basitrehmankhattak/weather_data_project)
Containerized end-to-end **ELT pipeline** ingesting live meteorological REST API data into `PostgreSQL`, transforming staging layers into analytics-ready marts with **`dbt` Core**, orchestrated via **Apache Airflow**, and monitored in **Grafana**.
- Built modular `dbt` staging and mart models with automated schema and data quality tests (`unique`, `not_null`).
- Orchestrated containerized tasks using Airflow's `DockerOperator` and built live `Grafana` dashboards tracking ingestion latency, row throughput, and pipeline health.
- **Tech:** Python, PostgreSQL, dbt Core, Apache Airflow, Grafana, Docker Compose.

### 2. [AWS Healthcare Big Data & MLOps Platform](https://github.com/Basitrehmankhattak/Aws-Healthcare-Bigdata-platform)
Event-driven **Medallion (`Bronze` / `Silver` / `Gold`) data lake** processing IoT telemetry and clinical batch records inside a private AWS VPC, with automated anomaly detection and cloud monitoring.
- **Tech:** AWS S3, Step Functions, Glue ETL, Athena, SageMaker, QuickSight, CloudWatch.

### 3. [Semantic News Recommendation Platform](https://github.com/Basitrehmankhattak/news-recommendation-platform)
Multi-stage recommendation pipeline on the Microsoft MIND dataset featuring sub-millisecond `FAISS` vector retrieval, `LightGBM` ranking, and diversity re-ranking via Maximal Marginal Relevance (MMR).
- **Tech:** Python, FastAPI, FAISS, LightGBM, PostgreSQL, Docker.

### 4. [HealthVision: End-to-End MLOps Platform](https://github.com/Basitrehmankhattak/healthvision-diabetes-mlops)
End-to-end clinical ML pipeline featuring scheduled `Apache Airflow` ingestion, schema validation, `FastAPI` REST inference, interactive `Streamlit` UI, and live `Grafana` monitoring.
- **Tech:** Apache Airflow, FastAPI, Streamlit, PostgreSQL, Grafana, Docker.

## Technical Skills

| Level | Tools & Technologies |
| :--- | :--- |
| **Core Data Stack** | Python (`pandas`, `requests`, `psycopg2`) · SQL (`PostgreSQL`, `MySQL` — CTEs, Window Functions, Query Optimization) · `dbt` Core (Dimensional Modeling, Schema Tests) · Apache Airflow (`DockerOperator`, `PythonOperator`) · ETL / ELT Pipelines · Docker & Docker Compose · Grafana · Git · Linux & Bash |
| **Cloud Platforms** | **Microsoft Azure** (Certified Administrator; `Entra ID / Azure AD`, VMs, RBAC) · **AWS** (`S3`, `EC2`, `ECS`, `Glue ETL`, `Athena`, `Step Functions`, `Lambda`, `SageMaker`, `CloudWatch`, `IAM`) |
| **Working Knowledge** | MongoDB · Power BI · Tableau · FastAPI · Streamlit · PyTorch · Scikit-Learn · LightGBM · FAISS · GitHub Actions / GitLab CI (`CI/CD`) |
| **Currently Building** | Snowflake (Cloud Data Warehouse) · Redis |
| **Infrastructure & Governance** | Linux (`Ubuntu`, `CentOS`, `RHEL`, `Debian`) · Windows Server (`AD DS`, `DNS`, `DHCP`, `GPO`) · `VMware ESXi` · `Hyper-V` · `Veeam` Backup & Recovery · `Okta` SSO · `Jira` (`JQL`, REST APIs) · `ServiceNow` · ITIL / CAB |

## Experience

### Global Infrastructure Engineer — u-blox
*Thalwil, Switzerland · Hybrid | May 2022 – Sep 2024*
- **Cloud Platform Operations:** Administered hybrid **Microsoft Azure** and **AWS** environments (`Entra ID`, VMs, RBAC, `EC2`, `ECS`, `S3`, `IAM`) with least-privilege access governance for global R&D teams.
- **Observability & Telemetry:** Built **Grafana** and **AWS CloudWatch** dashboards and automated alerting to track service availability, latency, and infrastructure health across international sites.
- **Workflow & REST API Automation:** Built `Python` and `Jira`/`Confluence` REST API & `JQL` automation scripts saving **15+ hours/month**, helping reduce the global ticket backlog by **80%** (1,000+ to <200 open tickets) with a **4.9/5 user satisfaction rating**.
- **Change Management & Disaster Recovery:** Led CAB change management for zero-downtime cloud migrations and executed full-site disaster recovery after a ransomware incident (`~200 machines` on-site within a `1,500-device` global recovery).

### Technical Support Infrastructure Engineer — Next Generation Technology Solutions (NGT Sol)
*Lahore, Pakistan · On-site | Sep 2021 – May 2022*
- **Operational Telemetry & SLA Reporting:** Extracted and analyzed incident, network, and uptime metrics from `ServiceNow`, `VeloCloud`, and `ITGlue` to produce recurring monthly SLA and performance reports for enterprise clients.
- **Identity Governance & Data Resilience:** Administered multi-site `Active Directory`, `Microsoft Entra ID / Office 365`, `Google Workspace`, and `Okta` SSO, and managed `VMware` / `Hyper-V` virtualization and `Veeam` backup and recovery.

## Education & Certifications
- **M2 Intelligent Systems & Computer Vision (SIVO)** — Université Sorbonne Paris Nord, Institut Galilée *(2026 – 2027)*
- **M1 MSc Data Science & Artificial Intelligence** — EPITA Paris *(90 ECTS, 14.69/20 GPA, Top 20%)*
- **B.S. in Computer Engineering** — COMSATS University Islamabad, Lahore Campus
- **Certifications:** Microsoft Certified: Azure Administrator Associate · DataCamp Associate Data Engineer in SQL · Microsoft Certified: Azure Fundamentals · Microsoft Certified: Azure AI Fundamentals
