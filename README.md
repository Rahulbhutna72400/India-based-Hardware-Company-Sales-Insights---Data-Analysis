# Atliq Hardware Sales Analysis

## 📜 Project Overview
Atliq Hardware, a hardware product company, faced declining sales and sought to uncover the root causes. This project analyzes their sales database to provide actionable insights and recommendations for reversing the decline and improving overall business performance.

### Objectives:
1. Identify reasons for declining sales.
2. Analyze regional, product, and customer performance.
3. Provide actionable recommendations to boost revenue.

---

## 📊 Dataset Description
The analysis is based on a relational database consisting of the following tables:

1. **`transactions`**: Contains details of sales transactions, including product, customer, region, quantity, and sales amount.
2. **`customers`**: Information on customer types and their categories (e.g., Brick & Mortar, E-Commerce).
3. **`markets`**: Regional and zone data for sales markets.
4. **`products`**: Details of products sold (e.g., product type and codes).
5. **`date`**: A temporal hierarchy to analyze trends over time.

---

## 🔍 Analysis Methodology
1. **Data Cleaning**:
   - Preprocessed data using MySQL to handle missing values and anomalies.
   - Rectified negative sales transactions and standardized data formats.

2. **Data Integration**:
   - Merged multiple tables for a comprehensive analysis of regions, customers, and product performance.

3. **Exploratory Data Analysis (EDA)**:
   - Identified key metrics like revenue, sales trends, and customer contributions.
   - Used MySQL for querying and Tableau for visualizing trends.

4. **Insights and Recommendations**:
   - Focused on actionable findings, such as optimizing product portfolios and addressing underperforming regions.

---

## 🚀 Tools and Technologies
- **SQL**: Data cleaning, preprocessing, and querying.
- **Tableau**: Interactive dashboards and data visualization.
- **Python**: Data analysis and visualization for in-depth exploration.
- **GitHub**: Repository for sharing and version control.

---

## 📈 Key Insights
1. **Regional Performance**:
   - The **North Zone** dominates sales, particularly in Delhi NCR, while the **South Zone** underperforms.
2. **Customer Trends**:
   - Brick & Mortar stores contribute 76% of sales, while E-Commerce remains an underutilized channel.
3. **Product Performance**:
   - A small subset of products drives most revenue, while others underperform significantly.
4. **Operational Challenges**:
   - Negative sales transactions, especially in E-Commerce, highlight potential issues in refund processes.
5. **Seasonality**:
   - Sales spikes during November and December suggest strong seasonal demand.

---

## 🛠️ Recommendations
1. **Boost E-Commerce**: Introduce targeted campaigns and enhance logistics for better customer experience.
2. **Expand in Underperforming Regions**: Focus on South Zone with tailored strategies.
3. **Optimize Product Portfolio**: Discontinue or rebrand consistently underperforming products.
4. **Fix Data Anomalies**: Refine refund processes and ensure accurate transaction reporting.
5. **Leverage Seasonal Trends**: Plan promotions and inventory for peak demand periods.

---

## 📂 Repository Structure
