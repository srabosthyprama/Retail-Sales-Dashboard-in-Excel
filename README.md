# Retail Sales Dashboard

An interactive retail sales dashboard built to analyze sales, profit, target achievement, regional performance, store performance, sales trends, and product performance.

The dashboard contains **3 pages**:

- Executive Summary
- Regional Performance
- Product Performance

---

## 1. Executive Summary

The Executive Summary provides an overall view of retail sales performance through **4 KPIs**:

- Total Orders
- Total Sales
- Total Profit
- Target Achievement

### Key Visuals & Insights

- **Regional Sales, Profit & Target Achievement:** Dhaka achieved the highest target performance, while Rangpur had the lowest target achievement.
- **Top 5 Stores by Sales:** Highlights the best-performing stores, with an option to switch and view the bottom-performing stores.
- **Monthly Sales Trend:** Shows sales trends over time, with a year slicer to compare **2025 and 2026**.
- **Sales Performance:** Highlights the top-performing salespeople and includes a note showing the contribution of the top 10 salespeople compared with the remaining salespeople.

### Interactive Filters

A **Month-Year slicer** allows users to analyze performance for a specific period. For example, selecting **Feb-2025** dynamically updates all KPIs and charts based on the selected period.

---

## 2. Regional Performance

The Regional Performance page focuses on comparing performance across different regions.

### KPIs

The page includes the same core KPIs as the Executive Summary:

- Total Orders
- Total Sales
- Total Profit
- Target Achievement

A **Region slicer** allows users to view KPI values for a specific region. By default, the KPIs show overall performance, but selecting a region such as **Khulna** updates the KPIs to display only Khulna's performance.

### Key Visuals & Insights

- **Regional Rating:** Shows which regions have high, medium, and low customer ratings.
- **Regional Sales vs Target:** A thermometer chart compares actual sales against the target. The **teal border represents the target**, while the **orange fill represents actual sales**, making it easy to identify regions that have met or fallen short of their targets.
- **Average Delivery Days:** A bar chart compares the average delivery time across regions.

### Regional Insights

- **Dhaka** has the lowest average delivery time and also has a higher proportion of **4–5 customer ratings**, indicating a possible relationship between faster delivery and better customer satisfaction.
- A detailed report shows that stores in Dhaka have average delivery times within approximately **2–3.5 days**, which may contribute to its stronger customer ratings.
- **Rangpur** has the highest average delivery time, generally between **5–7 days**, and also has the lowest customer ratings.

### Key Recommendation

The **Rangpur region should be prioritized for improvement**, particularly in reducing delivery times, as its higher delivery duration may be contributing to lower customer satisfaction and ratings.

The **View Details** option provides a deeper look into delivery time and customer rating patterns across regions.

---

## 3. Product Performance

The Product Performance page focuses on product sales, profitability, discount impact, and product-level performance.

### KPIs

- Total Quantity Sold
- Total Sales
- Total Profit
- Profit Margin

The KPIs dynamically change based on the selected **Category** and **Month-Year** slicers.

### Key Visuals & Insights

- **Discount vs Profit:** A scatter plot with a trendline is used to analyze the relationship between discount and profit. The trendline is slightly upward, while the **R² value is 0.0422**, indicating that discount explains approximately **4.2% of the variation in profit** in this analysis. This suggests that discounting has a relatively weak relationship with profit, and other factors may have a greater impact on profitability.
- **Sales vs Profit by Category:** Compares sales and profit performance across product categories.
- **Top 10 Best-Selling Products:** Highlights the products generating the highest sales, with an option to switch and view the bottom-performing products.

### Interactive Filters

Users can filter the dashboard by:

- Product Category
- Month-Year

The KPIs and visualizations update dynamically based on the selected filters.

---

## Key Business Insights

- **Dhaka** is the strongest-performing region in terms of target achievement and customer ratings.
- **Rangpur** requires attention due to its lower target achievement, longer delivery times, and lower customer ratings.
- Faster delivery appears to be associated with better customer ratings, particularly in Dhaka.
- The relationship between **discount and profit is relatively weak**, with an R² of **0.0422**, suggesting that other factors should be investigated to understand profitability.
- The dashboard enables users to identify **top and bottom-performing stores and products** for more focused business analysis.
- Interactive slicers allow users to explore performance by **region, category, and month-year** and dynamically analyze changes in KPIs and charts.

---

## Dashboard Pages

1. **Executive Summary** – Overall business performance and sales trends
2. **Regional Performance** – Regional sales, target, delivery, and customer rating analysis
3. **Product Performance** – Product sales, profitability, discount impact, and product ranking analysis
