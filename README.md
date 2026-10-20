# Colorado's Broadband Opportunity

[![Tableau Public](https://img.shields.io/badge/Tableau-Public-blue?logo=tableau)](https://public.tableau.com/app/profile/kristin.mooney/viz/TableauFiberAnalysis/ColoradosBroadbandOpportunity)
[![SQL](https://img.shields.io/badge/SQL-MySQL-orange?logo=mysql)](https://kristin-mooney.github.io/colorado-broadband/)

A four-dashboard Tableau story analyzing Colorado's competitive broadband landscape — identifying fiber expansion opportunities, competitive vulnerabilities, and churn risk. Built using FCC broadband data and IBM Telco Churn data, combining market analysis with customer retention modeling to support data-driven ISP strategy.

---

## [View the Live Dashboard on Tableau Public](https://public.tableau.com/app/profile/kristin.mooney/viz/TableauFiberAnalysis/ColoradosBroadbandOpportunity)

---

## Dashboard Overview

### Dashboard 1 — Broadband Landscape
![Broadband Landscape](<screenshots/Colorados Broadband Landscape.png>)

A high-level view of Colorado's current broadband coverage, provider distribution, and service gaps. Includes geographic coverage maps, provider market share, and technology type breakdowns across the state.

---

### Dashboard 2 — Competitive Battleground
![Competitive Battleground](<screenshots/The Competitive Battleground.png>)

Analyzes where providers are head-to-head and where underserved markets exist. Identifies counties and zip codes with limited competition, high incumbent concentration, and fiber buildout opportunity.

---

### Dashboard 3 — Expansion Strategy
![Expansion Strategy](<screenshots/Expansion Strategy.png>)

Prioritizes fiber expansion targets based on population density, existing infrastructure gaps, competitive exposure, and growth potential across Colorado communities.

---

### Dashboard 4 — Retention & Risk
![Retention and Risk](<screenshots/Managing Risk.png>)

Applies IBM Telco Churn modeling to identify customers most at risk of leaving. Surfaces churn risk factors and supports targeted retention strategy for ISPs operating in competitive markets.

---

## Key Findings

| Insight | Detail |
|---|---|
| Coverage Gaps | Significant underserved areas identified across rural Colorado counties |
| Competitive Pressure | Several high-density markets dominated by a single incumbent provider |
| Fiber Opportunity | Prioritized expansion zones identified by combining coverage and demand signals |
| Churn Risk | Key behavioral and demographic indicators of churn risk surfaced from telco data |
| Retention Strategy | At-risk customer segments identified for targeted intervention |

---

## Tools Used

- **MySQL** — data transformation and analysis queries
- **Tableau Desktop & Tableau Public** — four-dashboard story and publishing

---

## Data Sources

- **FCC Broadband Data (December 2025)** — provider coverage, technology type, and service area by geography
- **IBM Telco Churn Dataset (Kaggle, 2018)** — customer churn indicators and retention modeling

---

## Repository Structure

```
├── screenshots/
│   ├── dashboard1-broadband-landscape.png
│   ├── dashboard2-competitive-battleground.png
│   ├── dashboard3-expansion-strategy.png
│   └── dashboard4-retention-risk.png
├── sql/
│   └── broadband-analysis-queries.sql
└── README.md
```

---

*Built by [Kristin Mooney](https://kristin-mooney.github.io/) | [LinkedIn](https://linkedin.com/in/kristinmooney) | [Portfolio](https://kristin-mooney.github.io/colorado-broadband/)*
