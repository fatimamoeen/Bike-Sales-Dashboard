# 🚲 Bike Sales Analysis Dashboard — Excel

## Table of Contents
- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Data Transformation](#data-transformation)
- [Key Insights](#key-insights)
- [Business Recommendation](#business-recommendation)

---

## Introduction

I had the opportunity to complete a project using the **Bike Sales Dataset**. This analysis revolves around understanding customer purchase behavior for bikes across various demographic and lifestyle segments.

My goal was to journey through this dataset and create visual representations of the data to assess what drives a customer's decision to purchase a bike. I am primarily interested in analyzing purchase patterns — specifically concentrating on **income levels, age brackets, and commute distances** across gender groups.

By exploring this data with **Microsoft Excel**, I aimed to identify trends and patterns that can empower businesses to better target their customers, refine product offerings, and ultimately increase sales.

---

## Project Overview

| Aspect | Details |
|--------|---------|
| **Business Goal** | Identify which customer segments are most likely to purchase a bike so marketing teams can target high-value demographics and improve conversion rates |
| **Dataset** | Bike Buyers Dataset (publicly available) |
| **Time Frame** | Static cross-sectional dataset — no time series |
| **Grain** | One record per customer with purchase decision (Yes/No) |
| **Key Dimensions** | Gender, Age Bracket, Commute Distance, Education, Occupation, Marital Status, Cars Owned |
| **Key Facts** | Average Income, Purchase Decision (Yes/No), Number of People per segment |
| **Tools Used** | Microsoft Excel — Pivot Tables, Slicers, Bar Charts, Line Charts |

---

## Data Transformation

- Removed duplicate entries from the raw dataset
- Standardized abbreviated values: `M/F` → `Male/Female`, `Y/N` → `Yes/No`
- Created a new **Age Bracket** column using nested `IF` formulas:
  - Senior: 55+
  - Adult: 30–35
  - Young: Under 30
- Built pivot tables for each chart dimension
- Linked all slicers (Education, Occupation, Marital Status, Cars Owned, Home Owner) to pivot tables for full interactivity

---

## Key Insights

- **Higher income = higher purchase rate** — Male buyers averaged ~$60,124 vs ~$56,208 for non-buyers
- **Middle-aged adults (30–35) are the top buyers** — Peak purchase volume sits in this age bracket
- **Short commutes drive purchases** — Customers commuting 0–1 miles are significantly more likely to buy
- **Income gap is consistent across genders** — Female buyers also earned more on average than female non-buyers (~$55,774 vs ~$53,440)

---

## Business Recommendation

> Target marketing spend on **middle-aged professionals** with **shorter commutes** and **above-average income**. Bundle bike offerings with lifestyle messaging — fitness, convenience, leisure — rather than pure commute utility. The income data suggests emotional and lifestyle purchase drivers at this segment level.



## 📊 Dashboard Previews

![Bike Sales Dashboard](./dashboard_preview.png)

### Charts Included:
- **Avg Income Per Bike Purchase Decision** — Compares income across gender and purchase outcome
- **Age Bracket Per Bike Purchase Decision** — Purchase behavior across Senior (55+), Adult (30–35), and Young (Under 30) segments
- **Commute Distance Per Bike Purchase Decision** — How daily commute distance affects purchase likelihood

---

## 🔍 Key Insights

- **Higher income = higher purchase rate** — Males who purchased averaged ~$60K vs ~$56K for non-buyers
- **Middle-aged adults (30–35) are the top buyers** — Peak purchase volume sits in this age bracket
- **Short commutes drive purchases** — Customers commuting 0–1 miles are significantly more likely to buy, possibly for leisure use
- **Income gap is consistent across genders** — Female buyers also earned more on average than female non-buyers

---

## 🧹 Process

1. **Data Cleaning**
   - Removed duplicates
   - Standardized categorical values (e.g., M/F → Male/Female)   
2. **Data Preparation**
   - Created Age Bracket column using nested `IF` formulas
   - Built pivot tables for each chart dimension

3. **Dashboard Building**
   - Designed 3 core charts (bar, line)
   - Added slicers: Cars Owned, Education, Home Owner, Occupation, Marital Status
   - Linked all slicers to pivot tables for interactivity

---

## 🛠 Tools Used

| Tool | Purpose |
|------|---------|
| Microsoft Excel | Data cleaning, pivot tables, dashboard |
| Pivot Tables | Aggregation by segment |
| Slicers | Interactive filtering |
| Charts (Bar + Line) | Visual storytelling |

---

## 📁 File Structure

```
bike-sales-dashboard/
│
├── Bike_Sales_Dashboard.xlsx     # Main Excel file with dashboard
├── dashboard_preview.png         # Screenshot of final dashboard
└── README.md                     # This file
```

---

## 💡 Business Recommendation

> Target marketing spend on **middle-aged male professionals** with **shorter commutes** and **above-average income**. Bundle bike offerings with lifestyle messaging (fitness, convenience) rather than pure commute utility — the data suggests emotional/lifestyle purchase drivers at this income level.

---

## 👤 About

