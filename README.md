# Bike-Sales-Dashboard
An interactive Excel dashboard built to analyze bike purchase behavior across customer demographics. This project covers the full data analysis pipeline — from raw data cleaning to insight-driven visualization.

---

## 📌 Project Overview

This dashboard explores what drives a customer's decision to buy a bike. Using a real-world-style dataset, I identified patterns across income levels, age groups, commute distances, and more — all visualized through an interactive Excel dashboard with slicers.

**Key Question:** *What type of customer is most likely to purchase a bike — and why?*

---

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

