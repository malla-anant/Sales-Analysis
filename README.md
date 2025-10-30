📊 Regional Sales Analysis — Power BI Dashboard

📁 Project Overview
- The Regional Sales Analysis project aims to uncover key business insights from 5 years of U.S. sales data.
- This end-to-end data analysis project identifies regional performance patterns, product profitability, and customer segmentation using Exploratory Data Analysis (EDA) and an interactive Power BI dashboard.
- The project provides executives with a data-driven understanding of revenue trends, profit margins, customer behavior, and regional performance to help guide strategic business decisions.

🚩 Problem Statement
Sales teams often struggle with:
- Inconsistent revenue and profit performance across U.S. regions.
- Limited visibility into seasonal swings, top-performing SKUs, and channel profitability.
- Difficulty identifying growth opportunities and optimizing resources.

Goal:
Leverage 5 years of historical data to pinpoint growth levers, improve profitability, and optimize regional sales strategy.

🧭 Approach
Phase 1: Exploratory Data Analysis (EDA)
- Cleaned and joined multiple raw datasets (Sales, Customers, Products, Regions, Budgets).
- Conducted descriptive analysis to understand “What, Where & Why” behind sales trends.
- Used statistical measures and visual exploration to reveal seasonality, top performers, and correlations.

Phase 2: Interactive Dashboard
- Built a Power BI dashboard for business users to self-serve insights.
- Enabled slicing and filtering by time, product, region, and channel.

Created three analytical pages:
Page 1: Performance Summary
Page 2: Customer Segmentation
Page 3: Revenue Scenarios

🧹 Data Preprocessing
Steps performed:
- Merged tables: Sales, Customers, Products, Regions, Budgets, State–Region.
- Standardized and renamed columns.

Created derived metrics:
- Profit = Revenue - Cost
- Profit Margin % = (Profit / Revenue) × 100

Verified data integrity:
✅ No missing values
✅ No duplicates

Final Dataset Columns:
- Category	Columns
Identifiers	order_number, order_date, customer_name, channel, product_name
Financials	quantity, unit_price, revenue, cost, profit, profit_margin_pct
Calendar	order_month_name, order_month_num, order_month
Geography	state_code, state_name, us_region, lat, lon
Planning	budget_2017

📈 Key Insights
🕒 Seasonal Trends
- Pronounced revenue seasonality — peaks in May–June, dips in January–April.
- Annual sales cycle stabilized around $24M–$26M per month.

🧾 Product Insights
- Products 26 & 25 drive ~25% of total sales.
- High-Margin Products: Product 9 and Product 30 lead with ~40% margins.
- Strategy: Invest in top SKUs and optimize low-margin ones.

🌎 Regional Performance
- California contributes the highest revenue ($228M) and orders (7.6K).
- West Region leads with the highest profit margin (37.5%).
- Northeast underperforms, requiring targeted marketing.

🧍 Customer Insights
- Revenue highly concentrated — top 10 customers dominate.
- Aibox Company and State Ltd are top contributors.
- High-value clients (> $10M) with low margins (< 36%) need contract re-evaluation.

💰 Channel Analysis
- Wholesale: 54% of total sales volume.
- Export: Smaller share but highest average margin (~38%).
- Distributor: Moderate share and profitability.

🧩 Correlation Insights
Variable Pair	Correlation	Insight
Unit Price ↔ Revenue	0.91	Strong positive link — pricing drives revenue
Unit Price ↔ Profit	0.79	Profitability closely tied to pricing strategy
Revenue ↔ Profit	0.87	Direct relationship between top-line and bottom-line
Quantity ↔ Financials	≤ 0.34	Volume has minimal impact compared to pricing

💡 Recommendations
Seasonal Promotions:
- Boost offers in January and April to stabilize revenue dips.

SKU Optimization:
- Double down on high-performing products (26 & 25), phase out low-margin ones.

Channel Strategy:
- Expand Export partnerships for higher margins.
- Introduce volume incentives in Wholesale.

Regional Focus:
- Replicate California’s success model across regions.
- Strengthen marketing in the Northeast and Midwest.

Margin Monitoring:
- Track orders below 80% margin.
- Revisit pricing and cost control strategies.

📊 Power BI Dashboard Preview

Page 1 – Performance Summary
- Overview of total revenue, profit, and margin trends.
- Monthly revenue and profit patterns.
- Order value distribution and price-profit relationships.

Page 2 – Customer Segmentation
- Best-selling and most profitable products.
- Revenue and profit breakdown by sales channel.
- Strategic product positioning (Revenue vs. Profitability).

Page 3 – Revenue Scenarios
- Top customers and states by revenue.
- Regional revenue and margin breakdown.
- Total profit mapped by U.S. state.

🧠 Tools & Technologies
Tool	Purpose
- Power BI	Dashboard creation & visualization
- Python (Pandas, Matplotlib, Seaborn)	EDA and data cleaning
- Excel / CSV	Source data files
- Power Query	Data transformation
- DAX	Calculated measures for KPIs

📌 Project Workflow
Import & explore raw data
Clean and merge datasets
Perform EDA in Python
Design visuals and KPIs
Build Power BI dashboard
Generate insights & recommendations

🏁 Conclusion
This project delivers a comprehensive data-driven sales intelligence solution that helps management:
Identify key growth opportunities,
Optimize product and channel performance,
Align regional strategies with profit goals.

The Power BI dashboard empowers stakeholders to interactively explore sales performance and make informed business decisions in real time.

📂 Repository Structure

Sales-Analysis/

│

├── data/                     # Cleaned and processed datasets

├── notebooks/                # EDA notebooks (Python)

├── dashboard/                # Power BI file (.pbix)

├── reports/                  # PPT and summary report

├── images/                   # Dashboard screenshots

├── README.md                 # Project documentation

└── LICENSE


👨‍💻 Author
Malla Anant
