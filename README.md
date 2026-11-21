# Yunus Emre Kayaoğlu

**Data Engineer** — Lakehouse & ETL/ELT Specialist · MSc Student @ Karadeniz Technical University

```bash
$ whoami
Data Engineer @ Hangikredi — 2+ years building production ETL/ELT pipelines

$ focus --current
Data Vault 2.0 Lakehouse on Apache Spark, dbt & Iceberg
Data governance & quality with OpenMetadata
```

### How I think about data

```mermaid
flowchart LR
    subgraph SRC["Sources"]
        PG[(PostgreSQL)]
        ES[(Elasticsearch)]
        GA[GA4 / REST APIs]
        MIO[(MinIO)]
    end

    subgraph ORCH["Orchestration"]
        AF[Apache Airflow]
    end

    subgraph XFORM["Transform"]
        SPARK[Apache Spark]
        DBT[dbt]
    end

    LAKE[(Apache Iceberg<br/>Data Vault 2.0)]
    GOV[OpenMetadata]

    subgraph SERVE["Serve"]
        TRINO[Trino]
        MB[Metabase]
        API[FastAPI]
    end

    PG --> AF
    ES --> AF
    GA --> AF
    MIO --> AF
    AF --> SPARK --> DBT --> LAKE
    LAKE -. governed by .-> GOV
    LAKE --> TRINO --> MB
    LAKE --> API
```

### Stack

| | |
|---|---|
| **Languages** | Python · SQL |
| **Orchestration & Transform** | Apache Airflow · Apache Spark · dbt · Apache Iceberg · Trino |
| **Storage** | PostgreSQL · Elasticsearch · MinIO |
| **Governance & Modeling** | OpenMetadata · Data Vault 2.0 · Business Glossary |
| **Serving & Apps** | FastAPI · Streamlit · Metabase |
| **Tooling** | Docker · Git · Bitbucket · Linux · Jira |

### Experience

| Role | Company | Period |
|---|---|---|
| Data Engineer | Hangikredi | Jan 2025 – Present |
| Data Engineering Intern | Hangikredi | Jul 2024 – Jan 2025 |
| Data Scientist Intern | Karadeniz Technical University | Jul 2023 – Aug 2023 |

### Featured Projects

- **Explainable Visual Regression Testing** — automated pipeline for visual regression testing of web interfaces, combining block-level image comparison with DeepSeek-OCR and GPT-4o for semantic explanations.
- **AI-Powered Recommendation System Optimization** (TÜBİTAK 2209-A) — led a research project building data pipelines and ML models (XGBoost, LightGBM, CatBoost) for e-commerce recommendations, shipped as an interactive Streamlit app.

### GitHub Activity

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/yunusemrekayaoglu/yunusemrekayaoglu/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/yunusemrekayaoglu/yunusemrekayaoglu/output/github-contribution-grid-snake.gif" />
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/yunusemrekayaoglu/yunusemrekayaoglu/output/github-contribution-grid-snake.gif" width="100%" />
</picture>

<table>
<tr>
<td><img src="https://github-readme-stats.vercel.app/api?username=yunusemrekayaoglu&show_icons=true&theme=transparent&hide_border=true&title_color=3670A0&icon_color=3670A0&text_color=888888" alt="GitHub Stats" /></td>
<td><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=yunusemrekayaoglu&layout=compact&theme=transparent&hide_border=true&title_color=3670A0&text_color=888888" alt="Top Languages" /></td>
</tr>
</table>

### Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-3670A0?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/yunusemrekayaoglu)
[![GitHub](https://img.shields.io/badge/GitHub-3670A0?style=flat-square&logo=github&logoColor=white)](https://github.com/yunusemrekayaoglu)
[![Kaggle](https://img.shields.io/badge/Kaggle-3670A0?style=flat-square&logo=kaggle&logoColor=white)](https://www.kaggle.com/yunusemrekayaoglu)
[![Medium](https://img.shields.io/badge/Medium-3670A0?style=flat-square&logo=medium&logoColor=white)](https://medium.com/@yunusemrekayaoglu)
