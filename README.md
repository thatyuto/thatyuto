<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a73e8,100:34a853&height=180&section=header&text=Yutu%20Huang&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Data%20Engineering%20%C2%B7%20dbt%20%C2%B7%20Airflow%20%C2%B7%20BigQuery&descSize=18&descAlignY=58" alt="Yutu Huang banner" width="100%"/>

**MSc Computer Science and Engineering @ DTU** · Copenhagen 🇩🇰
BEng in Data Science and Big Data Technology

I turn one-off SQL analysis into tested, scheduled, reusable data models.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-yutowong-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yutowong/)
[![GitHub](https://img.shields.io/badge/GitHub-thatyuto-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/thatyuto)
![Status](https://img.shields.io/badge/Looking%20for-student%20data%20engineering%20role-34a853?style=for-the-badge)

</div>

---

## 🛠️ Tech stack

**Pipelines & orchestration**

![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![Spark](https://img.shields.io/badge/Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta%20Lake-00ADD4?style=flat-square&logo=delta&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)

**Warehouses & languages**

![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=databricks&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

**Infra & tools**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

## 🚀 Featured project

### [Modern E-commerce Data Platform](https://github.com/thatyuto/Modern-E-commerce-Data-Platform)

A solo batch data platform on the public Olist dataset (9 tables, ~1.55M rows). I explored in PostgreSQL first, then rebuilt the queries worth keeping as tested dbt models on BigQuery.

```mermaid
flowchart LR
    A[Olist CSV] --> B[BigQuery raw]
    B --> C[dbt staging]
    C --> D[dbt marts]
    D --> E[BI charts]
    F[Airflow daily 03:00] -.-> C
    F -.-> D
```

| 23 | 41 / 41 | ~34% |
|:---:|:---:|:---:|
| dbt models (star schema + 8 marts) | data tests passed in the last recorded run | less data scanned after partitioning (25.64 → 16.8 MB) |

- Daily Airflow schedule on Docker Compose, with retries
- Separate Spark + Delta Lake Medallion implementation on Databricks (not yet connected to BigQuery)

![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)

---

## 🧭 Other work

| Project | What I did | Stack |
|---|---|---|
| **LLM medication assistant**<br/>Alibaba Cloud Big Data Lab, 2022–2024 | Co-built a funded assistant with OCR and a multi-tier cache; also trained a Transformer on clinical time-series data for a sleep apnea study | Azure OpenAI, LangChain, Python |
| **Police Big Data Platform**<br/>Course project, 2024 | Real-time vehicle metrics with a monitoring dashboard | Kafka, Spark Streaming, HBase, Phoenix |
| **2D online competitive game**<br/>BEng thesis, 2024–2025 | Rating-based matchmaking and match replay | Spring Boot, Spring Cloud, WebSocket, Redis, Vue 3 |

---

## 📊 GitHub stats

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=thatyuto&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub stats"/>
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=thatyuto&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages"/>

</div>

---

## 🎯 Currently

- 🎓 Studying at DTU
- 🔧 Adding CI for `dbt test` to my data platform
- 🔗 Working on connecting the Spark pipeline to BigQuery

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:34a853,100:1a73e8&height=100&section=footer" alt="footer" width="100%"/>

</div>
