# Hey, I'm Aman Panchal

![Profile Views](https://komarev.com/ghpvc/?username=panchalaman&color=6c63ff&style=flat-square&label=Profile+Views)

### Data Engineer | AI & Data Science Background | Building the Data Layer That AI Runs On

I studied AI, Data Science, and Digital Business — and that's exactly why I moved into data engineering. I saw firsthand that the best ML model is worthless if the data pipeline feeding it is broken, late, or wrong. So now I build the infrastructure side: scalable ETL pipelines, dimensional data models, and cloud-native warehouses that make data reliable enough for AI to actually work.

I've worked with structured data, semi-structured formats, and genuinely messy unstructured sources (Python list strings embedded in CSVs — yes, really). Cleaning and normalizing that kind of data into something a model can consume is what I do.

This GitHub is where I learn in public. Every project here was built by hand, tested in the terminal, and documented like I'd want to read it myself.

---

### What I Work With

| Domain | Technologies |
| :--- | :--- |
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-Advanced-4479A1?style=flat&logo=postgresql&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-Shell-4EAA25?style=flat&logo=gnu-bash&logoColor=white) |
| **Compute & Processing** | ![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat&logo=apachespark&logoColor=white) ![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat&logo=duckdb&logoColor=black) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white) |
| **Cloud & Warehouse** | ![Azure](https://img.shields.io/badge/Microsoft%20Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white) ![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat&logo=snowflake&logoColor=white) ![BigQuery](https://img.shields.io/badge/Google%20BigQuery-669DF6?style=flat&logo=googlebigquery&logoColor=white) |
| **Orchestration** | ![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white) |
| **Containers & IaC** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white) ![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white) |
| **Streaming** | ![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat&logo=apachekafka&logoColor=white) |
| **Version Control** | ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white) |

---

### Why Data Engineering After AI

Most data engineers learn data engineering first. I went the other direction — I started with machine learning, understood what models need from the data layer, and then moved upstream to build it.

That means when I design an ETL pipeline or a star schema, I'm already thinking about what a data scientist or an ML model is going to do with the output. Feature tables, clean joins, no duplicates, no nulls where they shouldn't be. The data is ready when it arrives.

This is especially relevant for Gen-AI and LLM use cases — those systems consume massive amounts of structured and unstructured data, and someone needs to make sure that data is ingested, cleaned, versioned, and served reliably. That's what I'm building toward.

---

### Projects I've Built

These aren't hypothetical — every one has working code, documented SQL, and a README that explains the reasoning, not just the syntax.

| Project | What I did | Key techniques |
| :--- | :--- | :--- |
| [**Data Warehouse & Mart Build**](https://github.com/panchalaman/Data-Engineering-Journey/tree/main/Data-Engineering/SQL_COURSE/Projects/2_WH_Mart_Build) | End-to-end ETL pipeline — extract CSVs from Google Cloud Storage, load into a star schema, then build 4 specialized data marts (flat, skills demand, priority roles, company hiring). Incremental updates using MERGE for production-grade upserts. | Star schema, cloud extraction (GCS), MERGE upsert, additive measures, bridge tables, schema separation |
| [**Priority Jobs Pipeline**](https://github.com/panchalaman/Data-Engineering-Journey/tree/main/Data-Engineering/SQL_COURSE/Projects/4_Priority_Jobs_Pipeline) | Incremental ETL pipeline that tracks job postings by role priority. Built both the manual UPDATE+INSERT approach and a single-statement MERGE, then compared them side by side. Designed for production — handles schema evolution and idempotent re-runs. | Staging tables, upsert patterns, MERGE INTO, IS DISTINCT FROM, idempotent loads, schema evolution |
| [**Flat CSV to Star Schema**](https://github.com/panchalaman/Data-Engineering-Journey/tree/main/Data-Engineering/SQL_COURSE/Projects/3_Flat_to_WH_Build) | Took genuinely messy semi-structured data — skills stored as Python list strings like `['SQL', 'Python']` inside a CSV — and parsed, normalized, and loaded it into a proper star schema. Self-directed project, not from any course. | String parsing (REPLACE/SPLIT/UNNEST), semi-structured data handling, surrogate keys, bridge tables, FK constraints |
| [**Job Market EDA**](https://github.com/panchalaman/Data-Engineering-Journey/tree/main/Data-Engineering/SQL_COURSE/Projects/1_EDA) | 3 analytical queries to find the most in-demand skills, highest-paying skills, and best return on investment. Built a custom scoring formula using `LN()` to balance demand against salary — the kind of analysis that feeds into ML feature engineering. | Multi-table JOINs, MEDIAN, HAVING, logarithmic transformation, composite scoring |

### Learning Resources I've Written

| Resource | What's in it |
| :--- | :--- |
| [**SQL Course**](https://github.com/panchalaman/Data-Engineering-Journey/tree/main/Data-Engineering/SQL_COURSE/Lessons) | 15 lessons from zero to data-engineer-ready SQL — JOINs, window functions, CTEs, star schema design, ETL patterns, query optimization. All runnable in DuckDB. |
| [**Docker for Data Engineering**](https://github.com/panchalaman/Data-Engineering-Journey/tree/main/Learn%20Docker) | 15 lessons covering containers, images, Compose, networking, volumes, databases, Airflow, CI/CD pipelines, and security. Includes 3 hands-on projects and a command reference. |
| [**Linux & Git Fundamentals**](https://github.com/panchalaman/Data-Engineering-Journey/tree/main/Learn%20Linux) | File operations, grep/awk/sed, piping, permissions, shell scripting, and Git version control. |

---

### GitHub Stats

![Aman's GitHub Stats](https://github-readme-stats.vercel.app/api?username=panchalaman&show_icons=true&theme=dracula&hide_border=true&include_all_commits=true&rank_icon=github)

![GitHub Streak](https://streak-stats.demolab.com/?user=panchalaman&theme=dracula&hide_border=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=panchalaman&layout=compact&theme=dracula&hide_border=true)

---

### Get in Touch

I'm looking for data engineering roles where I can build scalable pipelines, design data models, and lay the groundwork for AI and ML systems that actually work in production. I'm based in Germany, fluent in English, and open to hybrid work.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/amanpanchal83)
[![Email](https://img.shields.io/badge/Email-Contact%20Me-D14836?style=for-the-badge&logo=gmail)](mailto:panchalaman@hotmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-Virsic.com-000000?style=for-the-badge&logo=googlechrome)](https://www.virsic.com)
[![Finance Project](https://img.shields.io/badge/Project-PlanYourFinance-25D366?style=for-the-badge&logo=googlechrome)](https://www.planyourfinance.de)

