# Hey, I'm Aman Panchal

![Profile Views](https://komarev.com/ghpvc/?username=panchalaman&color=6c63ff&style=flat-square&label=Profile+Views)

### 🚀 **Currently Open to Opportunities** | Data Engineer | AI & Data Science Background | Building the Data Layer That AI Runs On

> 📍 **Based in:** Berlin, Germany | Fluent English, Intermediate German | Open to hybrid, remote, or relocation
> 🎯 **Looking for:** Data Engineering roles in insurance, fintech, or AI/ML platforms
> ⚡ **Key Skills:** Snowflake, Python, SQL, Real-time Pipelines, Cloud Data Platforms, Modern Data Stack

I studied AI, Data Science, and Digital Business — and that's exactly why I moved into data engineering. I saw firsthand that the best ML model is worthless if the data pipeline feeding it is broken, late, or wrong. So now I build the infrastructure side: scalable ETL pipelines, dimensional data models, and cloud-native warehouses that make data reliable enough for AI to actually work.

I've worked with structured data, semi-structured formats, and genuinely messy unstructured sources (Python list strings embedded in CSVs — yes, really). Cleaning and normalizing that kind of data into something a model can consume is what I do.

Beyond the technical side, I bring insurance domain knowledge and a solid understanding of how the business actually works — the products, the processes, the people. I've led teams, communicated across departments, and I know that a pipeline only matters if the people downstream trust and use it.

This GitHub is where I learn in public. Every project here was built by hand, tested in the terminal, and documented like I'd want to read it myself.

---

### ⚡ Quick Navigation
**[Featured Snowflake Work](#snowflake-advanced-data-engineering-portfolio) | [All Projects](#projects-ive-built) | [Learning Resources](#learning-resources-ive-written) | [Philosophy](#my-data-engineering-philosophy) | [Contact Me](#get-in-touch)**

---

### What I Work With

| Domain | Cloud Services |
| :--- | :--- |
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-Advanced-4479A1?style=flat&logo=postgresql&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-Shell-4EAA25?style=flat&logo=gnu-bash&logoColor=white) |
| **Compute & Processing** | ![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat&logo=apachespark&logoColor=white) ![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat&logo=duckdb&logoColor=black) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white) |
| **Data Platforms & Warehousing** | ![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat&logo=snowflake&logoColor=white) ![dbt](https://img.shields.io/badge/dbt-FF6849?style=flat&logo=dbt&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white) ![Google BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=flat&logo=googlebigquery&logoColor=white) ![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white) |
| **Orchestration** | ![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white) |
| **Containers & IaC** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white) ![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white) |
| **Streaming** | ![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat&logo=apachekafka&logoColor=white) |
| **Version Control** | ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white) |
| **Languages** | Fluent in English, comfortable in German |

---

### My Data Engineering Philosophy

I approach data engineering with three core principles:

**1. Declarative Over Imperative** — I reach for Dynamic Tables and dbt first. If I can express *what* the data should be (not *how* to build it), I do. This reduces maintenance burden and lets Snowflake handle the heavy lifting.

**2. Data Quality is Non-Negotiable** — Garbage in equals garbage out. I design pipelines with built-in quality checks, dedupe logic, and clear ownership of data contracts.

**3. Cost-Conscious Architecture** — I right-size everything. Serverless Tasks instead of always-on warehouses. Auto-suspend on idle. Materialized views only where they matter. The goal: deliver business value without burning the cloud budget.

### Why Data Engineering After AI?

Most data engineers learn data engineering first. I went the other direction — I started with machine learning, understood what models need from the data layer, and then moved upstream to build it.

That means when I design an ETL pipeline or a star schema, I'm already thinking about what a data scientist or an ML model is going to do with the output. Feature tables, clean joins, no duplicates, no nulls where they shouldn't be. The data is ready when it arrives.

This background is especially relevant for Gen-AI and LLM use cases — those systems consume massive amounts of structured and unstructured data, and someone needs to make sure that data is ingested, cleaned, versioned, and served reliably. I'm building exactly that.

---

### Why I Stand Out

> I bring a **unique combination** that you don't often see together:
> - **ML/AI context** — I've worked on the other side of the data. I know what models want and need.
> - **Enterprise data engineering** — I design systems that scale: medallion architectures, cost optimization, governance, streaming pipelines.
> - **Hands-on Snowflake expertise** — Not just theory. I've built real systems with Streams, Dynamic Tables, Snowpark, masking policies, and Task DAGs.
> - **Clear communicator** — I document my work like I'm teaching it. Every project has a README that explains the reasoning, not just the syntax.
>
> **Result:** I design data systems that data scientists and ML teams actually want to use.

---

### Projects I've Built

These aren't hypothetical — every one has working code, documented SQL, and a README that explains the reasoning, not just the syntax.

| Project | What I did | Key techniques |
| :--- | :--- | :--- |
| [**Snowflake Advanced Data Engineering Portfolio**](https://github.com/panchalaman/snowflake-portfolio) 🎯 **FEATURED** | Enterprise-grade Snowflake portfolio showcasing real-world data platform design. I built a complete medallion architecture (Raw → Harmonized → Analytics) with 6 specialized modules: Real-time Streaming (Snowpipe + Streams + Tasks), Declarative Transformations (Dynamic Tables), Data Governance (Tag-based Masking, Row Access Policies), Snowpark Python integration, Secure Data Sharing, and FinOps/Cost Management. Every line is production-ready, heavily commented. GitHub Actions CI/CD included. This is what I'd deploy in a real organization. | Snowpipe, Streams, Serverless Tasks, Dynamic Tables, Snowpark Python, RBAC, Masking Policies, Data Sharing, GitHub Actions, schemachange |
| [**E-Commerce Analytics**](https://github.com/panchalaman/Data-Engineering-Journey/tree/main/Projects/ecom-analytics) | End-to-end batch pipeline for the Olist dataset (100k+ orders). Joined 9 raw CSVs locally using PySpark, loaded into partitioned PostgreSQL, transformed via 10 dbt models, and visualized via an interactive Streamlit dashboard. This was my first major project — it taught me how to think end-to-end. | PySpark, dbt, PostgreSQL (Partitioning & Indexing), Local-first Pipeline, Airflow DAGs, Streamlit |
| [**Data Warehouse & Mart Build**](https://github.com/panchalaman/Data-Engineering-Journey/tree/main/Data-Engineering/SQL_COURSE/Projects/2_WH_Mart_Build) 🎯 **FEATURED** | End-to-end ETL pipeline — extract CSVs from Google Cloud Storage, load into a star schema, then build 4 specialized data marts (flat, skills demand, priority roles, company hiring). Incremental updates using MERGE for production-grade upserts. This project taught me how to think about dimensional modeling and the importance of clear data contracts between layers. | Star schema, cloud extraction (GCS), MERGE upsert, additive measures, bridge tables, schema separation |
| [**Priority Jobs Pipeline**](https://github.com/panchalaman/Data-Engineering-Journey/tree/main/Data-types/4_Priority_Jobs_Pipeline) | Incremental ETL pipeline that tracks job postings by role priority. Built both the manual UPDATE+INSERT approach and a single-statement MERGE, then compared them side by side. Designed for production — handles schema evolution and idempotent re-runs. | Staging tables, upsert patterns, MERGE INTO, IS DISTINCT FROM, idempotent loads, schema evolution |
| [**Flat CSV to Star Schema**](https://github.com/panchalaman/Data-Engineering-Journey/tree/main/Data-Engineering/SQL_COURSE/Projects/3_Flat_to_WH_Build) | Took genuinely messy semi-structured data — skills stored as Python list strings like `['SQL', 'Python']` inside a CSV — and parsed, normalized, and loaded it into a proper star schema. Self-directed project, not from any course. | String parsing (REPLACE/SPLIT/UNNEST), semi-structured data handling, surrogate keys, bridge tables, FK constraints |
| [**Job Market EDA**](https://github.com/panchalaman/Data-Engineering-Journey/tree/main/Data-Engineering/SQL_COURSE/Projects/1_EDA) | 3 analytical queries to find the most in-demand skills, highest-paying skills, and best return on investment. Built a custom scoring formula using `LN()` to balance demand against salary — the kind of analysis that feeds into ML feature engineering. | Multi-table JOINs, MEDIAN, HAVING, logarithmic transformation, composite scoring |

| [**Advanced Data Engineering Modules (Snowflake)**](https://github.com/panchalaman/Data-Engineering-Journey/tree/main/advanced-data-engineering-snowflake) 🎯 **FEATURED** | 5 Complete Learning Modules with hands-on SQL, Python, and Streamlit code. I built API integrations, continuous streaming pipelines with CDC, dynamic aggregations, logging/alerting systems, Snowpark Jupyter notebooks, UDFs, Streamlit dashboards, Snowflake Native Apps, and Task orchestration DAGs. Each module includes a `LEARNING_NOTES.md` where I explain what I learned and why I made each architectural decision. Real data: weather (Hamburg) and food truck analytics (Tasty Bytes). | Snowflake API Integrations, JSON parsing, Streams & Tasks CDC, Dynamic Tables, Snowpark Notebooks, UDFs, Stored Procedures, Streamlit, Native Apps, Task DAGs, Email Notifications |

### Learning Resources I've Written

| Resource | What's in it |
| :--- | :--- |
| [**SQL Course**](https://github.com/panchalaman/Data-Engineering-Journey/tree/main/Data-Engineering/SQL_COURSE/Lessons) | 15 lessons from zero to data-engineer-ready SQL — JOINs, window functions, CTEs, star schema design, ETL patterns, query optimization. All runnable in DuckDB. |
| [**Snowflake Advanced Data Engineering**](https://github.com/panchalaman/Data-Engineering-Journey/tree/main/advanced-data-engineering-snowflake) | 5 complete modules covering Snowflake's modern data stack — API integrations, streaming with Snowpipe, CDC with Streams & Tasks, Dynamic Tables, Snowpark Python, UDFs, governance policies, and native app development. Includes learning notes for each module explaining real-world reasoning. |
| [**Docker for Data Engineering**](https://github.com/panchalaman/Data-Engineering-Journey/tree/main/Learn%20Docker) | 15 lessons covering containers, images, Compose, networking, volumes, databases, Airflow, CI/CD pipelines, and security. Includes 3 hands-on projects and a command reference. |
| [**Linux & Git Fundamentals**](https://github.com/panchalaman/Data-Engineering-Journey/tree/main/Learn%20Linux) | File operations, grep/awk/sed, piping, permissions, shell scripting, and Git version control. |

---

### GitHub Stats

![Aman's GitHub Stats](https://github-readme-stats.vercel.app/api?username=panchalaman&show_icons=true&theme=dracula&hide_border=true&include_all_commits=true&rank_icon=github)

![GitHub Streak](https://streak-stats.demolab.com/?user=panchalaman&theme=dracula&hide_border=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=panchalaman&layout=compact&theme=dracula&hide_border=true)

---

### Certifications & Professional Credentials

🏆 **Data Engineering Professional Certificate** (Snowflake) — Comprehensive training covering:
- Modern data stack design (Medallion architecture, ELT patterns)
- Continuous ingestion (Snowpipe, Snowpipe Streaming)
- Real-time transformations (Streams, Tasks, Dynamic Tables)
- Advanced analytics (Snowpark, UDFs, Stored Procedures)
- Enterprise governance (RBAC, Masking Policies, Object Tagging)
- Cost optimization (Resource Monitors, auto-suspend strategies)
- Data sharing and collaboration (Secure Views, Direct Shares)

**Portfolio:** [Explore my Snowflake advanced data engineering work](https://github.com/panchalaman/snowflake-portfolio) — A complete, production-ready reference architecture with 6 specialized modules demonstrating real-world enterprise patterns.

---

### Recent Highlights

- **June 2024:** Launched a complete Snowflake Advanced Data Engineering Portfolio with 6 enterprise modules
- **May 2024:** Built hands-on learning modules showcasing streaming CDC, dynamic tables, and governance
- **Ongoing:** Actively maintaining learning resources and building new data engineering patterns

### Beyond Code

I read a lot — Simon Sinek's work on leadership and purpose, Tony Robbins' *Life Force* on health and performance. I think good engineering comes from clear thinking, and clear thinking comes from taking care of yourself and understanding why you're building what you're building.

I'm convinced that the best engineers aren't just technically brilliant — they're curious about the business, they communicate clearly, and they care about making other people's jobs easier (whether that's another engineer or a data analyst).

---

### Get in Touch

**I'm actively looking for my next role.** I'm drawn to positions where I can:
- Design and own end-to-end data platforms
- Build systems for data scientists and ML teams to actually use
- Solve real business problems with scalable architecture
- Work with modern stacks (Snowflake, dbt, Streamlit, etc.)

**Ideal industries:** Insurance, fintech, AI/ML platforms, or any organization that takes data seriously.

**Let's talk:**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Let's%20Connect-0077B5?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/amanpanchal83)
[![Email](https://img.shields.io/badge/Email-Send%20Me%20a%20Message-D14836?style=for-the-badge&logo=gmail)](mailto:panchalaman@hotmail.com)
[![Portfolio](https://img.shields.io/badge/My%20Website-Virsic.com-000000?style=for-the-badge&logo=googlechrome)](https://www.virsic.com)
[![Finance Project](https://img.shields.io/badge/Side%20Project-PlanYourFinance-25D366?style=for-the-badge&logo=googlechrome)](https://www.planyourfinance.de)

