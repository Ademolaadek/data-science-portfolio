# 🛢️ Nigeria Oil & Gas Production Analysis (2000–2023)

![Python](https://img.shields.io/badge/Python-3.10-blue?style=flat-square&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-2.0-150458?style=flat-square&logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7-orange?style=flat-square)
![Seaborn](https://img.shields.io/badge/Seaborn-0.12-4C72B0?style=flat-square)
![Status](https://img.shields.io/badge/Status-Complete-10B981?style=flat-square)

> **An end-to-end exploratory data analysis uncovering the real drivers behind Nigeria's oil production decline — combining energy domain expertise with data science.**

---

## 📌 Project Overview

Nigeria is Africa's largest oil producer and a key player in global energy markets. Yet between 2010 and 2022, crude oil production fell by nearly **50%** — from 2.46 million barrels/day to just 1.22 million barrels/day.

This project investigates **why** — using 24 years of production, export, price, revenue, and pipeline security data to identify the root causes behind one of Africa's most significant energy crises.

**Key Question:** Is Nigeria's production decline driven by market forces (oil price) or operational/security factors (pipeline vandalism)?

---

## 🔍 Key Findings

| Finding | Insight |
|---|---|
| 🏆 Peak Year | 2010 — 2.46 million barrels/day |
| 📉 Lowest Year | 2022 — 1.22 million barrels/day (−50% from peak) |
| 💰 Highest Revenue | 2012 — ~$80 Billion USD |
| 🔗 Oil Price vs Production | Correlation = **0.03** (almost zero!) |
| ⚠️ Vandalism vs Production | Correlation = **−0.35** (negative — attacks hurt output) |
| ⛽ Gas vs Oil Production | Correlation = **−0.71** (Nigeria pivoted to gas as oil fell) |

> **Bottom line:** Nigeria's oil decline is **not market-driven** — it is **operationally driven**. Pipeline vandalism, militancy surges, and infrastructure degradation explain the collapse far better than oil prices do.

---

## 📊 Visualisations

### Chart 1 — Production vs Oil Price (2000–2023)
![Chart 1](chart1_production_vs_price.png)
> Production peaked in 2010 and declined sharply despite oil prices remaining high through 2014 — proving that price is not the primary driver of Nigeria's output.

---

### Chart 2 — Pipeline Vandalism vs Production
![Chart 2](chart2_vandalism_vs_production.png)
> The 2016 militancy surge produced 1,203 pipeline vandalism incidents — the same year production crashed to its lowest point in a decade. The visual correlation is striking.

---

### Chart 3 — Correlation Heatmap
![Chart 3](chart3_correlation_heatmap.png)
> Full correlation matrix across all 8 variables. Note the near-perfect relationship between production and exports (+0.98), and the inverse relationship between gas and oil production (−0.71) — evidence of Nigeria's gradual energy pivot toward LNG.

---

### Chart 4 — Annual Oil Revenue (2000–2023)
![Chart 4](chart4_revenue.png)
> Colour-coded revenue bars (green = high, amber = medium, red = low) reveal that even during the $100+/barrel era (2011–2014), declining production volumes eventually eroded revenue gains.

---

## 🧠 Skills Demonstrated

- **Exploratory Data Analysis (EDA)** — shape, dtypes, missing values, descriptive statistics
- **Data Visualisation** — dual-axis charts, annotated line plots, bar charts, heatmaps
- **Correlation Analysis** — identifying variable relationships and interpreting direction/strength
- **Domain Knowledge Integration** — linking data patterns to real-world events (militancy surges, COVID-19, financial crises)
- **Analytical Storytelling** — building a narrative from raw numbers to actionable recommendations
- **Python Libraries** — Pandas, NumPy, Matplotlib, Seaborn

---

## 🗂️ Project Structure

```
project-01-nigeria-oil-gas/
│
├── nigeria_oil_gas_analysis.ipynb   ← Full Jupyter Notebook
├── nigeria_oil_gas.csv              ← Dataset (generated)
├── chart1_production_vs_price.png   ← Visualisation 1
├── chart2_vandalism_vs_production.png ← Visualisation 2
├── chart3_correlation_heatmap.png   ← Visualisation 3
├── chart4_revenue.png               ← Visualisation 4
└── README.md                        ← This file
```

---

## 💡 Recommendations (Data-Driven)

1. **Pipeline Security Investment** — Vandalism has the clearest operational link to production loss. Security improvements in the Niger Delta would directly improve output.
2. **Accelerate Gas Monetisation** — The inverse oil/gas trend shows Nigeria is already pivoting. Doubling down on LNG export capacity is the right direction.
3. **Regional Drilling Strategy** — Rig count increased as production fell, suggesting effort without efficiency. Target new rigs in politically stable, low-vandalism regions.
4. **Revenue Diversification** — With oil price correlation near zero, Nigeria cannot count on price recovery to solve its production problem. Structural reform is needed.

---

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/Ademolaadek/data-science-portfolio.git

# Navigate to project folder
cd data-science-portfolio/project-01-nigeria-oil-gas

# Install dependencies
pip install pandas numpy matplotlib seaborn

# Open the notebook
jupyter notebook nigeria_oil_gas_analysis.ipynb
```

---

## 👤 Author

**Yussuf Ademola Adekunle**
Chemical Engineer | Data Scientist | Process & HSE Analyst

- 🔗 [LinkedIn](https://www.linkedin.com/in/yussuf-ademola-adekunle-gmnse-89b398178/)
- 📊 [DataCamp Portfolio](https://www.datacamp.com/portfolio/adek27)
- 🐙 [GitHub](https://github.com/Ademolaadek)

---

*Part of my [Data Science Portfolio](https://github.com/Ademolaadek/data-science-portfolio) — a collection of end-to-end projects across EDA, machine learning, NLP, and deployment.*
