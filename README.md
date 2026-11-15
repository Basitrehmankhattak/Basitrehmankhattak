# Basit ur Rehman
**Data & Analytics Engineer | Cloud, Linux & Data Platform Infrastructure | M2 Intelligent Systems & Computer Vision**  
Paris Region, France | [Portfolio](https://basitrehmankhattak.github.io/BasiturRehmanPortfolio/) | [LinkedIn](https://www.linkedin.com/in/basit-ur-rehman/) | basitrehman97@gmail.com

## About Me
- **Engineering Progression:** 3+ years administering and automating hybrid cloud (`AWS` / `Microsoft Azure`), Linux servers, relational databases (`PostgreSQL`/`MySQL`), telemetry dashboards (`Grafana`), and Python/REST API automation across **u-blox** and **Next Generation Technology Solutions**, now scaling directly into **Data & Analytics Engineering** (`Python`, `SQL`, `PostgreSQL`, `Snowflake`, `dbt`, `Apache Airflow`, `Docker`, `Grafana`).
- **Why Infrastructure + Data Engineering:** Experienced in operating the production foundation that modern data platforms rely on—cloud compute and object storage (`AWS S3/EC2/IAM`, `Azure`), RBAC/Entra ID identity governance, SQL database auditing, SLA metric reporting, and automated incident recovery—paired with hands-on ELT pipeline architecture, automated data quality testing, and dimensional modeling.
- **Target:** Seeking a 6-month End-of-Studies Master's Internship (*stage de fin d'études*) starting early 2027 in **Data Engineering** or **Analytics Engineering** in Île-de-France.

## Technical Toolkit

| Domain | Technologies & Tools |
| :--- | :--- |
| **Languages & Databases** | Python (`pandas`, `requests`, `psycopg2`), SQL (`PostgreSQL`, `Snowflake`, `MySQL` — CTEs, Window Functions [`DENSE_RANK`, `ROWS BETWEEN`], Complex Aggregations, Query Optimization), MongoDB, Bash / Shell Scripting |
| **Analytics Engineering & BI** | `dbt` Core (Staging/Intermediate/Mart Modeling, Schema & Data Quality Tests), Medallion Architecture (Bronze/Silver/Gold), Dimensional Modeling (Star & Snowflake Schemas), Grafana, Power BI, Tableau, Dataiku, Orange |
| **Orchestration & Pipelines** | Apache Airflow (`DockerOperator`, `PythonOperator`), ETL / ELT Architecture, REST APIs, Celery, Redis |
| **Cloud & Data Warehouses** | Snowflake, AWS (`S3`, `Glue ETL`, `Athena`, `Step Functions`, `Lambda`, `EC2`, `Security Groups`, `SageMaker`, `CloudWatch`, `IAM`), Microsoft Azure (Certified Admin, Entra ID / Azure AD, RBAC) |
| **Systems, Virtualization & Data Center** | Linux (`Ubuntu`, `CentOS`, `RHEL`, `Debian` — `SSSD`, `DNS`, `NFS`, `Samba`, `SSH`), Windows Server (`AD DS`, `DNS`, `DHCP`, `GPO`), OS Deployment & Imaging (`WDS`, `MDT`), VMware ESXi, Hyper-V, SAN Storage, VLANs, VPNs |
| **Identity, Security & DevOps** | Docker, Docker Compose, Git, GitLab CI / GitHub Actions (`CI/CD`), SSO, Conditional Access, MFA, Microsoft Intune, EDR/SOC Security Hardening, Jira Service Management (`JQL`, REST APIs), Confluence, ServiceNow, ITIL / CAB Governance |
| **AI & ML Systems** | Generative AI / LLMs, HuggingFace Transformers, FAISS, LightGBM, PyTorch, Scikit-Learn, FastAPI, Streamlit |

## Professional Experience

### Global Infrastructure Engineer — u-blox
*Thalwil, Zurich, Switzerland · Hybrid | May 2022 – Sep 2024 (2 yrs 5 mos)*
- **Cloud, Containers & Access Management:** Managed hybrid cloud infrastructure across Microsoft Azure (`Entra ID/Azure AD`, VMs, RBAC permissions) and AWS (`EC2`, `ECS` containerized workloads, `AWS CDK`, `S3`, security groups, `IAM` roles), ensuring strict least-privilege access control across global teams.
- **On-Premises, Virtualization & Global Disaster Recovery:** Executed on-premises server setups, hardware provisioning, hypervisor configurations (`VMware ESXi`, `Hyper-V`), and Linux/Windows OS deployments (`WDS`/`MDT`) across international sites, including full-site workstation and system recovery (`~200 R&D machines` on-site as part of a `1,500-device` global recovery) during a major ransomware incident with Active Directory offline.
- **Scripting & System Telemetry:** Developed Python scripts to automate daily system health checks, log parsing, and routine administrative workflows; configured **Grafana** and **AWS CloudWatch** telemetry dashboards and automated log alerts to track real-time infrastructure performance and service availability.
- **Workflow Automation & Governance (Jira / Confluence / CAB):** Led Jira & Confluence administration; built custom workflows, `JQL` queries, and REST API automation scripts saving **15+ operational hours monthly**, drove an **80% global ticket backlog reduction** (1,000+ to <200 open tickets) with a **4.9/5 user satisfaction rating**, and served as CAB Administrator enforcing ITIL change management for zero-downtime hybrid cloud migrations.
  
### Systems & Data Operations Engineer — Next Generation Technology Solutions (NGT Sol)
*Lahore, Punjab, Pakistan · On-site | Sep 2021 – May 2022 (9 mos)*
- **Log Parsing & Diagnostic Scripting:** Developed custom Shell and Python diagnostic scripts to parse system logs, automate routine server health checks, and resolve network/authentication bottlenecks.
- **Server Administration & Virtualization:** Delivered L2 infrastructure support across Linux and Windows server environments; executed routine server provisioning, virtualization setups (`VMware ESXi`), and security patch management.
- **Telemetry, Incident Data Metrics & SOPs:** Configured ITSM incident tracking workflows (`ServiceNow`) to structure operational logs and generate regular SLA performance and system uptime reports; drafted technical SOPs and deployment checklists to enforce infrastructure compliance.
- **Gouvernance d'identité & résilience des données :** Administration multi-sites d'`Active Directory` (contrôleurs de domaine, GPO, groupes de sécurité), `Microsoft Entra ID / Office 365`, `Google Workspace` et `Okta` SSO, ainsi que gestion d'environnements virtualisés (`VMware`, `Hyper-V`) et des sauvegardes `Veeam`.
  
## Featured Engineering Projects

### [AWS Healthcare Big Data & MLOps Platform](https://github.com/Basitrehmankhattak/Aws-Healthcare-Bigdata-platform)
- An event-driven Medallion (Bronze/Silver/Gold) data lake processing IoT telemetry and clinical batch records inside a private AWS VPC.
- **Tech:** AWS S3, Step Functions, Glue ETL, Athena, SageMaker Anomaly Detection, QuickSight, CloudWatch.

### [Automated Weather ELT & Observability Pipeline](https://github.com/Basitrehmankhattak/weather_data_project)
- A containerized end-to-end ELT pipeline ingesting live meteorological data, enforcing automated `dbt` schema quality tests (`unique`, `not_null`), orchestrating tasks via Airflow's `DockerOperator`, and tracking real-time metrics and ingestion health in Grafana.
- **Tech:** Python, PostgreSQL, dbt Core, Apache Airflow, Grafana, Docker Compose.

### [Production-Ready Semantic News Recommendation Platform](https://github.com/Basitrehmankhattak/news-recommendation-platform)
- A multi-stage recommendation funnel on the Microsoft MIND dataset featuring sub-millisecond vector retrieval and diversity re-ranking.
- **Tech:** Python, FastAPI, FAISS, LightGBM, Maximal Marginal Relevance (MMR), PostgreSQL, Docker.

### [HealthVision – End-to-End MLOps Medical Platform](https://github.com/Basitrehmankhattak/healthvision-diabetes-mlops)
- An end-to-end clinical machine learning system with automated Airflow ingestion pipelines, schema validation, REST inference, interactive UI, and live Grafana monitoring.
- **Tech:** Apache Airflow, FastAPI, Streamlit, PostgreSQL, Grafana, Docker.

  ## Education, Certifications & Languages
- **M2 Intelligent Systems & Computer Vision (SIVO)** — Université Sorbonne Paris Nord, Institut Galilée *(2026 – 2027)*
- **M1 MSc Data Science & Artificial Intelligence** — EPITA Paris *(Completed 90 ECTS, 14.69/20 GPA, Top 20%)*
- **B.S. in Computer Engineering** — COMSATS University Islamabad, Lahore Campus
- **Certifications:** Microsoft Certified: Azure Administrator Associate | DataCamp Associate Data Engineer in SQL | Microsoft Certified: Azure Fundamentals & Azure AI Fundamentals
- **Languages:** English (Fluent / C1) | French (Intermediate / B1) | Urdu / Hindi (Native)
