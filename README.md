# Powerbi-Manufacturing-Performance & Efficiency-Dashboard
Manufacturing operations dashboard measuring OEE, production output, shift performance, machine downtime, and operator productivity across a 9M-unit facility.
# 🏭 Nordex Manufacturing — OEE & Operations Dashboard

> **Power BI** | Manufacturing Analytics | Operations Intelligence

Manufacturing operations dashboard measuring OEE, production output, shift performance, machine downtime, and operator productivity across a 9M-unit facility.

---

## 📊 Dashboard Pages

| Page | Description |
|------|-------------|
| **Executive Overview** | High-level KPIs — OEE (74%), Availability (89%), Performance (86%), Quality (97%), Defect Rate (3%) |
| **Production Overview** | OEE trend, production volume by shift, downtime analysis by cause (Mechanical, Electrical, Calibration, Software, Preventive) |
| **Shift Overview** | OEE, downtime, unit output, and defect rate broken down by Morning, Evening, and Night shifts |
| **Machine Overview** | Per-machine availability, runtime hours, quality by shift, and weekly OEE trend |
| **Maintenance & Environment** | Maintenance issues by type, downtime resolved by technician, and temperature/humidity impact on performance |
| **Operator Performance** | Output per operator, defect rate ranking, skill level vs productivity, and operator experience impact |
| **Root Cause Analysis** | Drill-through table linking shift, skill category, date, and operator to defect data |

---

## 🔑 Key Metrics

| Metric | Value |
|--------|-------|
| OEE | 74% |
| Availability | 89% |
| Performance | 86% |
| Quality | 97% |
| Total Units | 9M |
| Output/Hour | 96 |
| Defect Rate | 3% |
| Runtime | 91K hrs |
| Downtime | 675K |

---

## 💡 Key Insights

- **Night shift** has the highest defect rate (4.4%) compared to Morning (2.2%) and Evening (3.5%), suggesting a need for targeted quality control during night operations.
- **Mechanical issues** are the leading cause of downtime (36.5K), followed by Electrical (25.6K) and Calibration (16.4K).
- **Morning shift** leads in both production output (3.9M units) and OEE (0.98), making it the most efficient shift.
- **Operator_32** is the top performer by output (136K units), while defect rates are consistent across the top 5 operators (~0.048).
- **Temperature and humidity** Temperature (20–25°C) and humidity (40–45%) remain stable and do not significantly influence performance.

---

## 🛠️ Tools & Skills Used

- **Power BI Desktop** — report development, DAX measures, data modelling
- **DAX** — KPI calculations, time intelligence, conditional formatting
- **Power Query** — data transformation and cleaning
- **Data Modelling** — star schema with fact and dimension tables
- **Visualisations** — KPI cards, line charts, bar charts, scatter plots, drill-through tables, slicers

---

## 📁 Files in This Repository

```
📂 powerbi-machine-performance-dashboard
 ┣ 📄 README.md               ← You are here
 ┣ 📊 Nordex_Dashboard.pbix   ← Power BI report file
 ┗ 📸 screenshots/            ← Dashboard preview images
    ┣ executive_overview.png
    ┣ production_overview.png
    ┣ shift_overview.png
    ┣ machine_overview.png
    ┣ maintenance_environment.png
    ┣ operator_performance.png
    ┗ root_cause_analysis.png
```

---

## 🚀 How to View

**Option 1 — Power BI Desktop (recommended):**
1. Download the `.pbix` file
2. Open in [Power BI Desktop](https://powerbi.microsoft.com/desktop) (free)
3. Explore all pages and slicers interactively

**Option 2 — NovyPro (live interactive view):**
👉 [View live dashboard on NovyPro](#) ← *(add your NovyPro link here)*

---

## 👤 About the Author

Data analyst specialising in Power BI dashboard development across HR, marketing, hospitality, and manufacturing sectors. I transform complex datasets into interactive, insight-driven reports that support strategic decision-making.

🔗 [LinkedIn](#) | 🌐 [NovyPro Portfolio](#) | 📧 [Email](horsfallinam@gmail.com)

---

> **Note:** The data used in this dashboard is fictitious and created solely for portfolio demonstration purposes.
