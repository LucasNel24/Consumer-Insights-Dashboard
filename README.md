# Consumer Insights Dashboard

## Overview
This project showcases an **interactive Power BI dashboard** designed to analyze consumer behavior, product performance, and engagement metrics for a global retail brand.  
The dataset is simulated to represent realistic omnichannel retail data, providing clear category-level differences, outliers, and performance variations for actionable storytelling.

The goal of this project is to present a **multi-page dashboard** with thematic sections, each focusing on a different dimension of consumer insights, enabling business teams to make data-driven decisions.

---

## Dataset
The dataset was structured to cover multiple business aspects and ensure variation across categories for clearer insights. It includes:

- **Date** – Transaction or event date.
- **Region** – Geographic market (e.g., North America, EMEA, APAC, Latin America).
- **Product Category** – Grouping of products (e.g., Running Shoes, Lifestyle, Apparel).
- **Channel** – Sales or engagement channel (e.g., Online Store, Physical Store, Third-Party Retailers).
- **Units Sold** – Number of products sold.
- **Revenue** – Total sales revenue (USD).
- **Return Rate (%)** – Percentage of products returned.
- **Customer Satisfaction Score** – Post-purchase rating (scale 1–10).
- **Social Engagement** – Social media interactions (likes, shares, comments).

Dataset size: **~1,000 rows**, spanning **January to December** for a full year’s view.

---

## Dashboard Structure

The dashboard is divided into **four pages**, each with a thematic focus:

### 1. Sales & Satisfaction Overview
- **KPIs** for total revenue, total units sold, and average customer satisfaction.
- **Monthly revenue trend** line chart.
- **Top & bottom performing product categories** by revenue.

<img width="1182" height="793" alt="Screenshot 2025-07-15 202419" src="https://github.com/user-attachments/assets/d7419f38-eba7-4e08-a671-9e71d5438faa" />


### 2. Channel Performance Analysis
- **Matrix table** comparing revenue, units sold, and return rates across channels and regions.
- **Heatmap** highlighting best and worst-performing combinations.
- **Slicer filters** for product category and time period.

<img width="1185" height="787" alt="Screenshot 2025-07-15 202444" src="https://github.com/user-attachments/assets/facc1e55-26ce-4f3a-9d28-d72ae3e8c99c" />

### 3. Social Engagement Insights
- **Scatter plot** showing correlation between social engagement and revenue.
- **Bar chart** comparing engagement by product category.
- Outlier detection to identify campaigns or products with unusually high/low engagement.

<img width="1123" height="635" alt="Screenshot 2025-07-15 202515" src="https://github.com/user-attachments/assets/5facb0cc-00fd-4d62-997b-cabbac3a8b8d" />

### 4. Customer Demographic Behaviour
- **Pie chart** showing sales share by region.
- **Stacked bar chart** comparing units sold by age group & product category.
- Insights into demographic preferences and regional trends.

<img width="1187" height="791" alt="Screenshot 2025-07-15 202535" src="https://github.com/user-attachments/assets/3a59e0b6-e5af-4fca-8280-31ff42d058ba" />

---

## Key Insights
1. **Certain product categories dominate revenue** in specific regions.
2. **Return rates vary significantly** by sales channel, with online channels seeing higher returns.
3. **Social engagement strongly correlates** with revenue for some categories, suggesting marketing leverage points.
4. **Customer demographics reveal niche opportunities** for targeted campaigns.

---

## Tools & Skills Used
- **Power BI** – Interactive visualizations and slicers.
- **Data Modeling** – Star schema with relationships between fact and dimension tables.
- **DAX** – Custom measures for KPIs and performance calculations.
- **Data Cleaning & Simulation** – Created realistic variations and outliers to enhance analysis.

---

## How to Use
1. Download the `.pbix` file from this repository.
2. Open in Power BI Desktop.
3. Use the slicers and drilldowns to explore insights by product, region, and channel.

---
