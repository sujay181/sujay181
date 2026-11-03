<h1 align="center">Hi 👋, I'm Sujay</h1>
<h3 align="center">I build data pipelines, then check whether the numbers are actually right.</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/sujay-narayana-646b17213/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://mail.google.com/mail/?view=cm&fs=1&to=sujaynarayana.181@gmail.com"><img src="https://img.shields.io/badge/Email-sujaynarayana.181%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Location-Australia-2E7D32?style=flat" alt="Location: Australia">
</p>

Data analyst and data engineer · Master of Data Science (Professional), Deakin University.

- 🟢 **Open to** data analyst and data engineer roles in Australia
- 🔭 Currently building a **healthcare data project**
- 🏗️ Building **[LedgerLake](https://github.com/sujay181/ledgerlake)** in public: a metadata-driven Databricks lakehouse, one layer a day
- 💬 Ask me about **medallion architecture, marketing attribution, DAX and Power BI, or why last-touch attribution lies**
- 📄 Published: *Livenessnet with Hardware Interface for higher Security*, IJARCCE 2023 ([DOI](https://doi.org/10.17148/IJARCCE.2023.125118))
- 📫 Reach me at `sujaynarayana.181@gmail.com`

### How I build

```mermaid
flowchart LR
    S["Sources<br/>SQL Server · PostgreSQL<br/>Salesforce · CSV"] --> B["Bronze<br/>raw, replayable"]
    B --> SV["Silver<br/>typed, deduplicated,<br/>quality-checked"]
    SV --> G["Gold<br/>star schema & KPIs"]
    G --> D["Dashboards<br/>Power BI · AI/BI"]
```

### Findings from my projects

| Finding | Project |
|---|---|
| **23%** of a $2M marketing budget misallocated by last-touch attribution | [mkt-intel](https://github.com/sujay181/mkt-intel) |
| **−77%** profit margin on orders discounted above 40% | [superstore-sales-eda](https://github.com/sujay181/superstore-sales-eda) |
| **≈0** measurable effect of heatwaves on daily road accidents in Victoria (p = 0.77) | [Victoria accidents](https://github.com/sujay181/Victoria-road-accidents-weather-analysis) |

### Tools

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI%20%C2%B7%20DAX-F2C811?style=flat&logoColor=black)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat&logo=databricks&logoColor=white)
![Apache Spark](https://img.shields.io/badge/PySpark-E25A1C?style=flat&logo=apachespark&logoColor=white)
![dbt](https://img.shields.io/badge/dbt%20Core-FF694B?style=flat&logo=dbt&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat&logo=duckdb&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

### Featured projects

| Project | What it shows |
|---|---|
| [**Marketing attribution platform**](https://github.com/sujay181/mkt-intel) | Scores six attribution models against known ground truth. Python, DuckDB, dbt, Spark |
| [**RetailQ lakehouse**](https://github.com/sujay181/retailq-databricks-lakehouse) | PostgreSQL, Salesforce and CSV into a Databricks medallion pipeline, star schema, metric view, AI/BI dashboard and Genie |
| [**Student Central dashboard**](https://github.com/sujay181/student-central-powerbi-dashboard) | Power BI dashboard on complaints, club engagement and alumni reach, built on a 455-record synthetic dataset I designed |
| [**LedgerLake**](https://github.com/sujay181/ledgerlake) | Metadata-driven Databricks lakehouse for a fictional neobank, with tests and CI (in progress) |
| [**Superstore sales EDA**](https://github.com/sujay181/superstore-sales-eda) | Finds where discounts and product mix erase profit |
| [**Victoria road accidents & weather**](https://github.com/sujay181/Victoria-road-accidents-weather-analysis) | Count models (Negative Binomial, GAM) in R |
