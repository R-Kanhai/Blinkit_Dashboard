# 🛒 Blinkit Grocery Sales Dashboard

An interactive **Power BI** dashboard analyzing sales performance across Blinkit's grocery outlet network — built to surface how sales are distributed by outlet type, size, location, and product category.
---

## 📌 Overview

This single-page report ("Home") gives a consolidated view of Blinkit's grocery sales data — how revenue is spread across outlet types, sizes, and locations, and how it breaks down by item category and fat content. It's designed as a quick, filterable snapshot rather than a multi-page drill-down report, so every visual updates instantly as filters are applied.


![Power BI](https://github.com/R-Kanhai/Blinkit_Dashboard/blob/main/Snapshot%20of%20Blinkit%20Analysis.png)
---

## 🗂️ Dashboard Contents

### Headline KPIs (top card)
A single multi-metric KPI card summarizing the whole dataset at a glance:

| Metric | What it shows |
|---|---|
| **Total Sum Sales** | Total sales value across all outlets |
| **Average Sales** | Average sale value per transaction/item |
| **No of Items** | Total count of items sold |
| **Avg Rating** | Average outlet/item rating |

### Visuals

| Visual | Chart Type | Breaks down |
|---|---|---|
| **Outlet Establishment** | Area Chart | Total Sales trended by the year each outlet was established |
| **Outlet Size** | Donut Chart | Total Sales share by outlet size (Small / Medium / High) |
| **Outlet Location** | Funnel Chart | Total Sales by outlet location type (Tier 1/2/3) |
| **Outlet Type** | Matrix / Pivot Table | Outlet Type vs. Total Sales, No of Items, Average Sales, Avg Rating, and Item Visibility |
| **Fat Content** | Donut Chart | Total Sales split by item fat content (Low Fat / Regular) |
| **Item Type** | Bar Chart | Total Sales by grocery item category |
| **Fat by Outlet** | Clustered Bar Chart | Total Sales by outlet location type, split further by fat content |

A secondary dynamic KPI card sits alongside the donut/slicer panel and updates based on the **Metric** selector described below.

---

## 🎛️ Filters & Interactivity

- **Outlet Location Type** slicer
- **Outlet Size** slicer
- **Item Type** slicer
- **Metric** selector — a dynamic field-parameter-style slicer that lets viewers swap which KPI drives the adjoining visual, without needing separate charts for each metric
- A **reset/refresh button** to clear all active filter selections back to default
- Full cross-highlighting: clicking any chart segment filters the rest of the page

---

## 🛠️ Tech Stack

- **Power BI Desktop** — data modeling, DAX, report design
- **Power Query** — data cleaning and transformation of the raw grocery dataset
- **DAX** — core measures (Total Sum Sales, Average Sales, No of Items, Avg Rating) and the dynamic metric-switching logic

---

## 🚀 How to Explore

1. Open `blinkit_project.pbix` in Power BI Desktop, **or**
2. View the interactive version via the Publish-to-Web link above (no login required)
3. Use the **Outlet Location, Outlet Size, and Item Type slicers** to filter the whole page.
4. Use the **Metric slicer** to switch what the dynamic card/chart displays
5. Click any donut segment, bar, or funnel stage to cross-filter the rest of the report
6. Use the reset button to clear all filters back to the default view

---

## 📁 Repository Contents

```
├── blinkit_project.pbix     # Power BI report file
├── /screenshots              # Dashboard preview images
└── README.md
```

---

## 📬 Contact

Built by **Rohan Kanhai** as part of a Power BI portfolio project .

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rkanhai/) [![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rohankanhai55@gmail.com)

- **LinkedIn:** [linkedin.com/in/rkanhai](https://www.linkedin.com/in/rkanhai/)
- **Email:** [rohankanhai55@gmail.com](mailto:rohankanhai55@gmail.com)

*Note: This project uses the public Blinkit grocery sales dataset for demonstration purposes.*
