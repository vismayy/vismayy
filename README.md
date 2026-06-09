<div align="center">

# Vismay Shah

**Data & Business Analytics Professional**

Toronto, ON &nbsp;·&nbsp; [LinkedIn](https://linkedin.com/in/vismayy) &nbsp;·&nbsp; [vismay0210@gmail.com](mailto:vismay0210@gmail.com)

![Profile Views](https://komarev.com/ghpvc/?username=vismayy&color=1B3A5C&style=flat-square&label=Profile+Views)

</div>

---

## 👋 About Me

I build end-to-end analytical pipelines that find the answers data is hiding — the kind that change how a business competes.

**7+ years** of analytical work across energy operations (Gujarat Gas Limited), CPG market intelligence (WX Brands · Bread & Butter Wines), and financial data management. I went from Mechanical Engineering to building 6-CTE T-SQL pipelines, Python ETL systems, and Power BI dashboards that get adopted as production business tools.

The project I'm most proud of: I led a national market intelligence co-op engagement for **WX Brands (Bread & Butter Wines)** as Team Lead. The original work was delivered in Excel. It wasn't good enough. Over the following 18 months I rebuilt the entire analysis from scratch — Python, SQL Server, Power BI — because I wasn't willing to accept the quality of my first version.

> **Seeking:** Data Analytics · Business Analytics · Operations Analytics &nbsp;|&nbsp; **Industries:** Energy · CPG · Financial Services · Consulting

---

## 🛠️ Tech Stack

**Languages & Data Engineering**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![T-SQL](https://img.shields.io/badge/T--SQL-CC2927?style=flat-square&logo=microsoft-sql-server&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square&logo=microsoft-sql-server&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![statsmodels](https://img.shields.io/badge/statsmodels-3776AB?style=flat-square&logo=python&logoColor=white)

**Business Intelligence & Visualization**

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Microsoft Excel](https://img.shields.io/badge/Excel%20%2B%20VBA-217346?style=flat-square&logo=microsoft-excel&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)

**Platforms & Tools**

![Azure](https://img.shields.io/badge/Microsoft%20Azure-0089D6?style=flat-square&logo=microsoft-azure&logoColor=white)
![SAP](https://img.shields.io/badge/SAP%20MM-0FAAFF?style=flat-square&logo=sap&logoColor=white)
![Salesforce](https://img.shields.io/badge/Salesforce-00A1E0?style=flat-square&logo=salesforce&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## 📌 Featured Project

### [🍷 Bread & Butter Wines — National Market Intelligence](https://github.com/vismayy/bread-butter-wine-analysis)

> **Real client co-op engagement · WX Brands · Team Lead · Built Sep 2024 – 2026**

The Canadian wine market contracted **-3.46% YoY** in 2024. Bread & Butter grew **+27%** and reached the **#1 position among all USA-origin wine brands in Canada.** This project explains how — and where the next opportunities are.

| Layer | What was built |
|-------|----------------|
| **Python ETL** | OOP pipeline normalizing AB/BC monthly and ON/QC 13-period fiscal calendars into a unified analytical model |
| **T-SQL Model** | 6-CTE pipeline — HHI market concentration, CR3/CR5/CR10, tier segmentation, strategic archetypes |
| **Forecasting** | Seasonal OLS with promotional de-biasing · **R² = 0.90 · MAPE = 9.9%** |
| **Power BI** | Intelligence Board, Pricing Analysis Leaderboard, Regional Deep Dives |
| **Findings** | 4 strategic stories across 9 varietals and 4 provinces — Quebec gap, BC threat, Pinot Noir stronghold, 3000ml opportunity |

**The key analytical insight — why de-biasing matters:**

```python
# Price promotions drive +155% average sales lift per activated period.
# Forecasting from raw sales embeds promotional spikes into the organic baseline.
# The fix: train the model with promo flags as regressors, then zero them at forecast time.

future_df[promo_cols] = 0       # All promos off
future_df['price_dev']  = 0     # Baseline price, no discount

# What remains is structural organic demand — what would sell without any promotion.
pred = model.get_prediction(future_df)
```


---

## 🎓 Education

| Credential | Institution | Year | Result |
|-----------|-------------|------|--------|
| Post-Graduate Certificate — Analytics for Business Decision Making | George Brown College, Toronto | 2024 | 3.89 / 4.00 · Dean's List · Honours |
| Post-Graduate Certificate — Big Data Analytics | Georgian College, Barrie | 2023 | 82.83% · Dean's List · Honours |
| B.Tech — Mechanical Engineering | Nirma University, India | 2018 | 7.49 / 10 · Merit Scholarship |

---

## 📜 Certifications

Microsoft Certified: Power BI Data Analyst Associate (PL-300) – Jan 2026
Microsoft Excel Expert (MO-201) – Aug 2025
Microsoft Certified: Azure Data Fundamentals (DP-900) – Jan 2026


---

## 🤝 Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Vismay%20Shah-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/vismayy)
&nbsp;
[![Email](https://img.shields.io/badge/Email-vismay0210%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:vismay0210@gmail.com)

---

<div align="center">
<sub>Building analytical tools that find the answers data is hiding.</sub>
</div>
