# Just-Store-Sales-Performance-Analysis
An Exploratory Tableau Dashboard for Sales, Profit, and Product Strategy

## Project Overview

This project presents a comprehensive **Tableau-powered exploration** of sales, profit, discounting behavior, and product performance for **Just-Store**, a retail company operating across multiple customer segments and geographies. With data from 9,994 transactions, this project focuses on uncovering actionable insights from key metrics and answering executive-level business questions.

🔗 **Live Dashboard**: [View on Tableau Public](https://public.tableau.com/app/profile/oladayo.oladapo/viz/JustStoreDashboard/ExecutiveView?publish=yes)

---

## Business Background

Just-Store is an emerging retail player offering diverse products to both individual and corporate clients. The company is undergoing regional expansion and needs better visibility into:
- Product profitability
- Sales performance by region/category
- Discounting behavior
- Customer churn & repeat purchases

Understanding these dynamics is critical to **strategy, marketing**, and **operational efficiency**.

---

## Problem Statement

- Sales performance varies significantly by region and product line.
- High customer churn in some segments
- Profit erosion due to inconsistent discounting
- Limited understanding of time-based trends
- Data preparation inconsistencies reducing analytic efficiency

---

## Project Objectives

- Analyze sales performance across **regions**, **categories**, and **time**.
- Identify **high-performing and underperforming products**.
- Visualize trends using **Tableau dashboards**.
- Optimize decision-making with **clear KPIs and insights**.
- Interpret **distribution behavior** from descriptive statistics.

---

## Dataset Metrics (Descriptive Statistics Summary)

### Sales
- **Mean**: 229.86 | **Median**: 54.49 | **Mode**: 12.96  
- **Skewness**: 12.97 | **Kurtosis**: 305.31  
✅ *Highly skewed with extreme high-value sales outliers.*

### Quantity
- **Mean**: 3.79 | **Median/Mode**: 3  
- **Skewness**: 1.28 | **Kurtosis**: 1.99  
✅ *Most orders fall between 2–4 units, normally distributed.*

### Discount
- **Mean**: 15.6% | **Median**: 20% | **Mode**: 0%  
- **Skewness**: 1.68  
✅ *Many orders have no discounts, but a long tail of high-discount transactions affects margins.*

### Profit
- **Mean**: $28.66 | **Median**: $8.67 | **Std. Dev**: $234.26  
- **Skewness**: 7.56 | **Kurtosis**: 397.18  
✅ *Wide spread in profitability with many zero or negative profit orders.*

---

## Tableau Dashboards

### Executive Overview (Main Dashboard)
- Sales by **Region** (West, East, Central, South)
- Sales by **Category** (Technology, Furniture, Office Supplies)
- Monthly trend line chart for **Sales Over Time**
- Profit contribution per category
- Order count, customer base, and quantity sold KPIs

### Table View (Supporting Detail)
- Individual customer order-level metrics
- Sales, quantity, and profit breakdown
- Allows drill-down on losses, high-ticket sales, and regional anomalies

---

## Key Insights

### Profitability
- **Profit skewed heavily**: Some products generate high margins while many incur losses (negative profit).
- **Technology category** shows the highest profit, followed by Furniture.

### Discount Effect
- High discount values (up to 80%) significantly erode profit.
- Discounts are **common**, but not always effective for revenue lift.

### Regional Performance
- **West Region** leads in both sales and profit.
- **Central & South** underperform; needs marketing or logistics optimization.

### Product Categories
- **Technology** contributes 40% of all sales.
- **Office Supplies**, despite volume, shows **lowest profit** share.

### Sales Trends Over Time
- Seasonal spikes observed (especially in Q4).
- Tableau dashboard allows **monthly filtering** for strategic planning.

---

## Recommendations

- Cap excessive discounts beyond 30% unless tied to volume thresholds.
- Prioritize marketing in high-performing regions (**West**) and develop strategies for Central/South.
- Use quantity and re-order analysis to drive **loyalty-based incentives**.
- Focus BI on **profitability heatmaps by category-region combination**.
- Monitor and segment **loss-making transactions** to reduce leakages.

---

## Tools Used

- Tableau (Data Visualization)
- Excel (Data Cleaning & Prep)
- GitHub (Documentation & Dataset Hosting)

---

## Repository Contents

| File | Description |
|------|-------------|
| `just_store_sales_data.csv` | Cleaned transactional dataset |
| `JustStoreDashboard.twbx` | Tableau packaged workbook |
| `JustStoreDashboard.pdf` | Dashboard in PDF |
| `README.md` | Project documentation file (this file) |

---

## Skills Demonstrated

✅ Exploratory Data Analysis  
✅ Distribution & Descriptive Statistics Interpretation  
✅ Tableau Dashboard Design  
✅ Business-Oriented Data Storytelling  
✅ Performance Optimization Recommendations

---

## published Dashboard

👉 [**Just-Store Executive Dashboard on Tableau Public**](https://public.tableau.com/app/profile/oladayo.oladapo/viz/JustStoreDashboard/ExecutiveView?publish=yes)

