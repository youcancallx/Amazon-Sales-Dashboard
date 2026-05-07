# Amazon-Sales-Dashboard
 Project Overview
This project focuses on analyzing Amazon sales data to track key performance indicators (KPIs) and understand consumer buying patterns. The dashboard provides a comprehensive view of sales trends, product performance, and fulfillment efficiency.

Objective: To identify high-growth product categories and optimize inventory based on regional demand.

Business Impact: Helps stakeholders understand which factors (e.g., promotions, fulfillment methods, or seasonality) drive the most revenue.

 Key Insights & KPIs
Total Revenue & Profit: Monthly and quarterly growth trends.

Order Status Distribution: Tracking Shipped, Cancelled, and Pending orders to measure fulfillment success.

Product Analysis: Identifying top-selling categories (e.g., Electronics, Apparel) and individual SKUs.

Geographical Sales: A map view showing sales concentration across different states/regions.

Fulfillment Comparison: Analysis of Amazon vs. Merchant (FBA vs. FBM) fulfillment performance.

 Tech Stack
Visualization: Power BI / Tableau

Data Cleaning: Power Query (Transforming raw CSV data, handling nulls in 'Promotion' and 'Amount' columns).

Analysis: DAX for calculated measures like Year-over-Year (YoY) Growth and Profit Margin %.

Documentation: Microsoft Excel for initial data audit.

 Data Transformation Steps
Data Scrubbing: Removed duplicate entries and handled missing values in critical columns like Amount and Courier Status.

Date Formatting: Converted raw date strings into a proper Date Table to allow for Time Intelligence analysis (MoM, YoY).

Calculated Columns: Created custom groups for 'Order Size' (Small, Medium, Large) to better categorize customer behavior.

Schema: Developed a Star Schema for optimized dashboard performance.

 Dashboard Preview
(Upload your screenshot to your GitHub repo and link it here)

 Business Recommendations
Inventory Management: Increase stock for top-performing categories during peak months identified in the trend chart.

Marketing Focus: Target underperforming regions with specific promotional campaigns.

Fulfillment Strategy: Shift more products to Amazon fulfillment (FBA) if data shows lower cancellation rates compared to Merchant fulfillment.
