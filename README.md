# 📊 Money Changer Sales Dashboard 2025

An interactive **Power BI** dashboard for monitoring foreign exchange (money changer) sales performance, covering revenue, net profit, margin, and performance by branch and currency.

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Status](https://img.shields.io/badge/status-completed-brightgreen)

---

## 🎯 Project Goal

This dashboard was built to help money changer management:
- Monitor **total revenue** and **net profit** in real time.
- Measure **net margin (%)** against a defined target.
- Compare sales performance across **branches**.
- Analyze revenue and profit trends **month over month**.
- View sales contribution broken down by **currency type**.

---

## 🗂️ Dashboard Structure

The dashboard consists of **2 pages**:

### Page 1 — Performance Overview
| Visual | Function |
|---|---|
| Card | Total Revenue |
| Card | Total Net Profit |
| Card | Net Margin (%) |
| Card | Net Profit (value) |
| Gauge Chart | Net Margin (%) vs Target Margin |
| Clustered Column Chart | Total Revenue by Branch |
| Line Chart | Monthly Revenue Trend |
| Line Chart | Monthly Net Profit Trend |
| Slicer | Filter by Branch |
| Slicer | Filter by Currency Code |
| Slicer | Filter by Date |

### Page 2 — Detailed Analysis
| Visual | Function |
|---|---|
| Clustered Bar Chart | Total Revenue by Currency Code |
| Pivot Table | Net Profit Breakdown by Month & Branch |
| Slicer | Filter by Branch, Currency, and Date |

---

## 📐 Key Metrics

Core DAX measures used in this dashboard:
- **Total Revenue** — total value of sales transactions.
- **Total Net Profit** — net profit from the buy-sell exchange rate spread.
- **Net Margin (%)** — ratio of net profit to revenue.
- **Target Margin** — benchmark margin displayed on the gauge chart.

## 🧩 Data Dimensions

The dashboard uses the following dimensions for filtering and grouping:
- `Branch` — money changer branch/location.
- `Currency Code` — type of foreign currency transacted.
- `Month` / `Date` — transaction time period.

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** — data modeling and visualization.
- **DAX (Data Analysis Expressions)** — measure calculations such as revenue, profit, and margin.
- **Power Query** — data transformation and cleaning before loading into the model.

---


## 📌 Insights You Can Explore

- Which branch contributes the most revenue?
- How do monthly revenue and net profit trend — stable, growing, or seasonal?
- Which currency is transacted the most and generates the highest profit?
- Is the current net margin meeting the target?

---

## License

This project is licensed under the MIT [LICENSE](LICENSE) use it freely for learning, teaching, or building.
```
  _    _ _  ______  _   _ 
 | |  | | |/ / __ \| \ | |
 | |  | | ' / |  | |  \| |
 | |  | |  <| |  | | . ` |
 | |__| | . \ |__| | |\  |
  \____/|_|\_\____/|_| \_|                
```


This project was created as part of a data analysis and visualization portfolio using Power BI.

If you have any feedback or questions about this dashboard, feel free to open an issue or reach out directly.
