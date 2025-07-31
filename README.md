
# 🧾 Madhav Store Sales Dashboard - Power BI Project

This project demonstrates a complete sales analysis dashboard for a fictional retail brand — **Madhav Store** — using **Microsoft Power BI Desktop**. It covers key business metrics like Total Sales, Total Profit, and Quantity Sold with interactive filters and dynamic insights.

---

## 📌 Project Features

- 📅 **Date-wise Sales Analysis**
- 🌍 **Region-wise Performance Breakdown**
- 🧺 **Product Category & Sub-Category Insights**
- 📈 **Trendline Analysis using DAX**
- 📊 **Interactive Charts and Filters**
- 🧠 **Business Insights using Measures and KPIs**

---

## 🛠️ Tools & Techniques Used

| Tool       | Usage                                   |
|------------|------------------------------------------|
| Power BI   | Data Modeling, Visualizations, Dashboard |
| Power Query| Data Cleaning and Transformation         |
| DAX        | Measures, Calculated Columns             |
| CSV File   | Source data (Sales data)                 |

---

## 📂 Project Structure

```
📁 MadhavStore_SalesDashboard/
├── test_data.csv
├── dashboard.pbix
├── images/
│   └── dashboard_screenshot.png
└── README.md
```

---

## 📷 Sample Dashboard View

## 📊 Key Measures Used

```DAX
Total Sales = SUM(Sales[Sales])
Total Profit = SUM(Sales[Profit])
Total Quantity = SUM(Sales[Quantity])
Profit Margin = DIVIDE([Total Profit], [Total Sales])
```

---

## 📥 How to Use

1. Open `dashboard.pbix` using Power BI Desktop.
2. Load the provided `test_data.csv` file.
3. Explore the dashboard with filters and slicers.
4. Modify or expand with your own visuals or metrics.

---

## 🧠 Business Questions Answered

- Which region had the highest profit?
- What product categories are most profitable?
- Are there seasonal trends in sales?
- Which customer segment drives the most revenue?

