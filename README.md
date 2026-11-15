# Basit ur Rehman
**Data & Analytics Engineering Intern (*Stage de fin d'études* · 6 Months · Feb/Mar 2027) | Python · SQL · dbt · Apache Airflow · Docker**  
Paris Region, France (Île-de-France) | [Portfolio](https://basitrehmankhattak.github.io/BasiturRehmanPortfolio/) | [LinkedIn](https://www.linkedin.com/in/basit-ur-rehman/) | basitrehman97@gmail.com

## About Me
- **Engineering Profile:** Master 2 student in Intelligent Systems & Computer Vision at **Université Sorbonne Paris Nord** (following M1 Data Science & AI at **EPITA Paris**) with **3+ years of European and international production infrastructure experience** across **u-blox** (Switzerland) and **NGT Sol**.
- **Data Engineering + Production Infrastructure:** Combines hands-on **ETL/ELT pipeline engineering**, **dimensional data modeling**, and **automated data quality testing** (`Python`, `SQL`, `PostgreSQL`, `Snowflake`, `dbt` Core, `Apache Airflow`, `Docker`, `Grafana`) with proven enterprise experience in hybrid cloud governance (`AWS`, `Microsoft Azure`), Linux operations, REST API automation, and SLA observability.
- **Availability (*Stage de fin d'études*):** Seeking a **6-month End-of-Studies Master's Internship starting February/March 2027** (*convention de stage* provided by Université Sorbonne Paris Nord) in **Data Engineering**, **Analytics Engineering**, or **Data Platform Engineering** in Île-de-France. Bilingual working environment: **English (C1)** & **French (B1)**.

## Technical Toolkit

| Domain | Technologies & Tools |
| :--- | :--- |
| **Languages & Databases** | Python (`pandas`, `requests`, `psycopg2`), SQL (`PostgreSQL`, `Snowflake`, `MySQL` — CTEs, Window Functions [`DENSE_RANK`, `ROWS BETWEEN`], Complex Aggregations, Query Optimization), MongoDB, Bash / Shell Scripting |
| **Analytics Engineering & BI** | `dbt` Core (Staging / Intermediate / Mart Modeling, Schema & Data Quality Tests), Medallion Architecture (Bronze / Silver / Gold), Dimensional Modeling (Star & Snowflake Schemas), Grafana, Power BI, Tableau |
| **Orchestration & Data Pipelines** | Apache Airflow (`DockerOperator`, `PythonOperator`), ETL / ELT Pipelines, Data Ingestion, REST APIs, Celery, Redis |
| **Cloud & Data Warehouses** | Snowflake, AWS (`S3`, `EC2`, `ECS`, `AWS CDK`, `Glue ETL`, `Athena`, `Step Functions`, `Lambda`, `SageMaker`, `CloudWatch`, `IAM`), Microsoft Azure (Certified Admin, `Entra ID / Azure AD`, VMs, RBAC) |
| **Linux, Virtualization & Backup** | Linux (`Ubuntu`, `CentOS`, `RHEL`, `Debian` — `SSH`, `DNS`, `NFS`), Windows Server (`AD DS`, `DNS`, `DHCP`, `GPO`), `VMware ESXi`, `Microsoft Hyper-V`, `Veeam Backup & Replication` |
| **DevOps, Security & Governance** | Docker, Docker Compose, Git, GitLab CI / GitHub Actions (`CI/CD`), Identity Governance (`SSO`, `Okta`, `Conditional Access`, `MFA`), Jira (`JQL`, REST APIs), Confluence, ServiceNow, ITIL / CAB Change Management |
| **AI & ML Systems** | FastAPI, PyTorch, Scikit-Learn, LightGBM, FAISS, HuggingFace Transformers, Generative AI / LLMs, Streamlit |

## Featured Engineering Projects

### 1. [Automated Weather ELT & Observability Pipeline](https://github.com/Basitrehmankhattak/weather_data_project)
- Architected a containerized end-to-end **ELT pipeline** ingesting live meteorological REST API data into `PostgreSQL`, transforming raw staging tables into analytics-ready marts with **`dbt` Core**, and enforcing automated data quality tests (`unique`, `not_null`).
- Orchestrated containerized tasks via **Apache Airflow** (`DockerOperator`) and built real-time **Grafana** observability dashboards tracking ingestion latency, row throughput, and pipeline health.
- **Tech:** Python, PostgreSQL, dbt Core, Apache Airflow, Grafana, Docker Compose.

### 2. [AWS Healthcare Big Data & MLOps Platform](https://github.com/Basitrehmankhattak/Aws-Healthcare-Bigdata-platform)
- Designed an event-driven **Medallion (`Bronze` / `Silver` / `Gold`) data lake** processing IoT telemetry and clinical batch records inside a private AWS VPC with automated anomaly detection and cloud monitoring.
- **Tech:** AWS S3, Step Functions, Glue ETL, Athena, SageMaker Anomaly Detection, QuickSight, CloudWatch.

### 3. [Production-Ready Semantic News Recommendation Platform](https://github.com/Basitrehmankhattak/news-recommendation-platform)
- Engineered a multi-stage recommendation pipeline on the Microsoft MIND dataset featuring sub-millisecond `FAISS` vector retrieval, `LightGBM` ranking, and diversity re-ranking via Maximal Marginal Relevance (MMR).
- **Tech:** Python, FastAPI, FAISS, LightGBM, PostgreSQL, Docker.

### 4. [HealthVision – End-to-End MLOps Medical Platform](https://github.com/Basitrehmankhattak/healthvision-diabetes-mlops)
- Built an end-to-end clinical ML pipeline featuring scheduled `Apache Airflow` data ingestion, automated schema validation, `FastAPI` REST inference, interactive `Streamlit` UI, and live `Grafana` monitoring.
- **Tech:** Apache Airflow, FastAPI, Streamlit, PostgreSQL, Grafana, Docker.

## Professional Experience

### Global Infrastructure Engineer — u-blox
*Thalwil, Zurich, Switzerland · Hybrid | May 2022 – Sep 2024 (2 yrs 5 mos)*
- **Cloud Compute, Containers & Identity Governance:** Administered hybrid cloud infrastructure across **Microsoft Azure** (`Entra ID / Azure AD`, VMs, RBAC) and **AWS** (`EC2`, `ECS` containerized workloads, `AWS CDK`, `S3`, security groups, `IAM`), enforcing least-privilege access governance across global R&D teams.
- **System Telemetry & Observability (`Grafana` / `CloudWatch`):** Configured real-time **Grafana** and **AWS CloudWatch** telemetry dashboards and automated log alerting to monitor service availability, latency, and infrastructure health across international sites.
- **REST API & Python Workflow Automation:** Built `Python` automation scripts and `Jira` / `Confluence` REST API & `JQL` workflows saving **15+ operational hours/month**, drove an **80% global ticket backlog reduction** (1,000+ to <200 open tickets) with a **4.9/5 user satisfaction rating**, and led CAB change management for zero-downtime hybrid cloud migrations.
- **Virtualization & Global Disaster Recovery:** Administered `VMware ESXi`, `Hyper-V`, and Linux/Windows infrastructure across international offices, executing full-site disaster recovery (`~200 R&D machines` on-site within a `1,500-device` global recovery) during a critical ransomware incident with Active Directory offline.

### Technical Support Infrastructure Engineer — Next Generation Technology Solutions (NGT Sol)
*Lahore, Punjab, Pakistan · On-site | Sep 2021 – May 2022 (9 mos)*
- **Operational Telemetry & SLA Reporting:** Extracted, structured, and analyzed incident, network, and uptime metrics across `ServiceNow`, `VeloCloud`, and `ITGlue` to produce recurring monthly SLA compliance and infrastructure performance reports for enterprise clients.
- **Enterprise Identity Governance & Data Resilience:** Administered multi-site `Active Directory` (Domain Controllers, GPOs, security groups), `Microsoft Entra ID / Office 365`, `Google Workspace`, and `Okta` SSO access controls, while managing `VMware`/`Hyper-V` virtualization and `Veeam` backup/recovery workflows.

## Education, Certifications & Languages
- **M2 Intelligent Systems & Computer Vision (SIVO)** — Université Sorbonne Paris Nord, Institut Galilée *(2026 – 2027)*
- **M1 MSc Data Science & Artificial Intelligence** — EPITA Paris *(Completed 90 ECTS, 14.69/20 GPA, Top 20%)*
- **B.S. in Computer Engineering** — COMSATS University Islamabad, Lahore Campus
- **Certifications:** Microsoft Certified: Azure Administrator Associate | DataCamp Associate Data Engineer in SQL | Microsoft Certified: Azure Fundamentals & Azure AI Fundamentals
- **Languages:** English (Fluent / C1) | French (Intermediate / B1 — comfortable in bilingual teams) | Urdu / Hindi (Native)
