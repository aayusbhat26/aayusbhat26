<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
    <img src="assets/banner-light.svg" alt="Aayush Kumar Bhat — Backend and Data Engineer" width="100%">
  </picture>
</p>

Backend and data engineer. I build services and pipelines that stay correct when data is late, duplicated, or malformed — Python/FastAPI on the serving side, PySpark and Delta Lake on the processing side.

**Now** — Associate Software Engineer at Nagarro, Gurugram  
**Focus** — streaming correctness, medallion pipelines, query performance  
**Open to** — remote backend and data engineering roles

---

### 01 / Selected systems

**Globe News Atlas**  
Ten public sources → bronze/silver/gold Parquet lake on Hugging Face → FastAPI → React/Three.js globe.  
[Live](https://globe-news-atlas.onrender.com/) · [Code](https://github.com/aayusbhat26/globe_news_atlas)

**TaskFlow**  
Chat-native work OS spanning 62 Prisma models, with Socket.IO presence, threads, reactions, and one Docker service on Render.  
[Live](https://taskflow-render.onrender.com/en) · [Code](https://github.com/aayusbhat26/task_flow)

### 02 / Open source

**[apache/iceberg-python #4169](https://github.com/apache/iceberg-python/pull/4169)** — merged. `list-refs` now emits one JSON object per ref, so CLI output parses cleanly downstream.

### 03 / How I build

```mermaid
flowchart LR
    A[Sources] -->|Python · ADF| B[Ingest]
    B -->|Parquet| C[Storage]
    C -->|PySpark · DuckDB| D[Transform]
    D -->|tests · quarantine| E[Quality]
    E -->|FastAPI · Power BI| F[Serve]
```

Correctness before dashboards: I write the data-quality checks before the reporting layer.

### 04 / Writing

- [How to integrate Clerk in a Next.js application](https://dev.to/aayusbhat26/how-to-integrate-clerk-in-next-js-application--4hba)
- [dev.to/aayusbhat26](https://dev.to/aayusbhat26)

### 05 / Stack

`Python` `SQL` `PySpark` `Delta Lake` `DuckDB` `Azure Data Factory` `Databricks` `AWS` `FastAPI` `PostgreSQL` `Prisma` `TypeScript` `React` `Docker` `GitHub Actions`

### 06 / Contact

[Portfolio](https://aayush-portfolio-390a.onrender.com/) · [LinkedIn](https://www.linkedin.com/in/aayush-kumar-bhat-/) · [LeetCode](https://leetcode.com/u/Aayush_Kumar_Bhat_08/) · [work.aayush.bhat@gmail.com](mailto:work.aayush.bhat@gmail.com)
