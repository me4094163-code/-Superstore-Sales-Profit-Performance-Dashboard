# 📊 Superstore Sales & Profit Performance Dashboard

## 📌 Project Overview

This interactive **Power BI** dashboard analyzes the sales and profitability performance of a retail Superstore across **2019–2020**. It provides stakeholders with an at-a-glance view of core financial metrics, quarterly sales trends, product category profitability, and shipping mode contributions—complete with dynamic filtering by **Region** and **Sub-Category**.

## 🖼️ Dashboard Preview

> *Replace `./dashboard_preview.png` below with the exact filename of your uploaded screenshot in the repository.*

## 🎯 Key Performance Indicators (KPIs)

| Metric | Value | Description | 
| ----- | ----- | ----- | 
| **Total Sales** | **\$1.34M** | Cumulative revenue generated across all regions and categories (2019–2020). | 
| **Total Profit** | **\$175.23K** | Net profit generated from overall sales. | 
| **Profit Margin** | **13.05%** | Overall profitability ratio (`Total Profit / Total Sales`). | 
| **Profit per Order** | **\$58.37** | Average profit earned per individual order. | 

## 🎛️ Interactive Features & Slicers

The left navigation pane enables dynamic cross-filtering across all visuals:

* **Region Slicer:** Filter performance across `Central`, `East`, `South`, and `West`.

* **Sub-Category Slicer:** Drill down into 17 product sub-categories (`Accessories`, `Appliances`, `Art`, `Binders`, `Bookcases`, `Chairs`, `Copiers`, `Envelopes`, `Fasteners`, `Furnishings`, `Labels`, `Machines`, `Paper`, `Phones`, `Storage`, `Supplies`, and `Tables`).

## 📈 Visual Breakdown & Key Insights

### 1. Sum of Sales by Year and Quarter *(Line Chart)*

* **Strong Seasonality:** Sales exhibit a clear Q4 peak in both years—rising sharply in **Oct 2019** (\~\$0.24M) and reaching an overall high in **Oct 2020** (\~\$0.28M), followed by a post-holiday dip in Q1 (Jan).

* **Year-over-Year Growth:** Overall sales momentum improved in 2020 compared to 2019, starting at a higher Q1 baseline (\~\$0.12M vs. \~$0.09M) and achieving a stronger year-end peak.

### 2. Sum of Sales and Sum of Profit by Category *(Clustered Column Chart)*

* **Technology:** The top-performing category, leading in both total sales (\~\$0.50M) and total profit (\~$90K).

* **Office Supplies:** Delivers solid revenue (\~\$0.43M) alongside healthy profit margins (\~$75K).

* **Furniture:** Generates comparable sales volume (\~\$0.41M) to Office Supplies, yet produces disproportionately low profit (\~$10K), signaling a critical margin bottleneck.

### 3. Sum of Profit by Ship Mode *(Pie Chart)*

| Ship Mode | Total Profit | Share of Profit | 
| ----- | ----- | ----- | 
| **Standard Class** | \$99.74K | **56.92%** | 
| **Second Class** | \$36.94K | **21.08%** | 
| **First Class** | \$29.75K | **16.98%** | 
| **Same Day** | \$8.81K | **5.03%** | 

* **Standard Class** drives more than half of the company's total profit, while **Same Day** shipping accounts for only \~5% of net profit.

## 💡 Business Recommendations

1. **Audit Furniture Pricing & Discounts:** Despite generating \~\$0.41M in revenue, Furniture yields minimal profit. Review discounting policies, supplier costs, and shipping expenses specifically for low-margin sub-categories like `Tables` and `Bookcases`.

2. **Capitalize on Q4 Demand:** Increase inventory readiness and targeted marketing campaigns heading into Q4 (October–December), while introducing Q1 promotional bundles to cushion the January revenue drop.

3. **Scale High-Margin Categories:** Expand cross-selling strategies around top-performing **Technology** and **Office Supplies** items to boost the overall `13.05%` profit margin.

4. **Evaluate Shipping Cost Structure:** Maintain operational efficiency in **Standard Class** fulfillment while assessing whether **Same Day** delivery fees adequately cover fulfillment costs.

## 🛠️ Tools & Techniques Used

* **Tool:** Microsoft Power BI Desktop

* **Data Modeling & Calculations:** DAX measures for KPIs:

```
Total Sales = SUM(Orders[Sales])
Total Profit = SUM(Orders[Profit])
Profit Margin = DIVIDE([Total Profit], [Total Sales], 0)
Profit per Order = DIVIDE([Total Profit], DISTINCTCOUNT(Orders[Order ID]), 0)

```

* **Design:** Custom rounded KPI cards, tile slicers, consistent blue brand palette, and clean visual hierarchy.

## 🚀 How to Use

1. Clone this repository:

```
git clone https://github.com/me4094163-code/superstore-performance-dashboard.git

```

2. Open the `.pbix` file in **Microsoft Power BI Desktop**.

3. Use the **Region** and **Sub-Category** slicers on the left panel to explore specific market segments.

## 📬 Contact

Created by **Mohamed Essam** – feel free to reach out!

* **LinkedIn:** [Mohamed Essam](https://www.linkedin.com/in/mohamed-essam-009a2132a)

* **GitHub:** [me4094163-code](https://github.com/me4094163-code)

* **Email:** [Me4094163@gmail.com](mailto:Me4094163@gmail.com)


