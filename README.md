🛍️ Shopify ProfitGuard: Sales & Operational Audit Dashboard
A comprehensive, three-page interactive Power BI suite designed to identify profit leaks, analyze return volatility, and optimize discounting strategies for a global e-commerce operation.

2. Short Description / Purpose
The Shopify ProfitGuard Dashboard is a strategic auditing tool built to analyze over 60,000 sales records. Its primary purpose is to move beyond surface-level sales metrics to uncover the "hidden costs" of business—specifically focusing on how aggressive discounting and high return rates impact the net bottom line. It provides actionable insights for stakeholders to recover lost margins and stabilize operational performance.

3. Tech Stack
The dashboard was built using the following tools and technologies:

📊 Power BI Desktop – Core platform for end-to-end report development.

📂 Power Query – Used for advanced data cleaning, date normalization, and return-status logic.

🧠 DAX (Data Analysis Expressions) – Developed custom measures for Profit Margin, Return Rate %, and Cumulative Shipping Loss.

📝 Data Modeling – Optimized a star-schema inspired model to ensure fast cross-filtering between traffic sources, product categories, and geographic regions.

4. Data Source
Source: Shopify Sales Dataset from Kaggle website.
The dataset contains granular transaction data including order_date, product_category, discount_percent, traffic_source, and is_returned status across multiple global territories.

5. Features / Highlights
📉 Business Problem
Despite strong top-line revenue, the business was experiencing "margin erosion." Analysts lacked visibility into why certain months faced profit dips and couldn't quantify the exact cost of returned goods and inefficient 40% discount tiers.

🎯 Goal of the Dashboard
To deliver a three-tier audit that:

Identifies the most profitable categories and payment methods.

Quantifies the financial impact of the 16.5% return rate peak.

Provides a 2027 roadmap for discount optimization and shipping cost recovery.

🔍 Walkthrough of Key Visuals
Category Revenue Leaderboard (Bar Chart): Ranks performance across sectors, highlighting Electronics as the primary driver with $8.7M in revenue.

Monthly Return Velocity (Line Chart): Tracks the stability of returns over time. Identifies a systemic baseline of 14.8% and critical spikes reaching 16.5%.

Discount Sensitivity Analysis (Area Chart): Shaders profit area against discount tiers, visually proving that discounts over 15% drain margin without increasing order volume.

Logistics Loss Table: A detailed breakdown of the $119,444 lost in shipping costs due to returned items, categorized by traffic source (Organic/Social).

Geographic Sales Map: Visualizes global purchasing power and identifies regional "Return Hotspots."

💡 Business Impact & Insights
Past Performance: Confirmed Electronics and Accessories as the core revenue anchors.

Present Challenge: Identified a $119k shipping leak caused by volatile return rates that are currently unmanaged.

Future Strategy: Recommended a 15% discount cap to protect net margins and targeted a 2% reduction in returns to save $16,000+ annually in logistics.


