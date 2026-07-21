# Retail Customer Shopping Behavior Analysis

## 📊 Project Overview
A leading retail company sought to better understand its customers' shopping behavior to improve sales, customer satisfaction, and long-term loyalty[cite: 2]. Management noticed shifting purchasing patterns across demographics and sales channels, requiring a deep dive into the factors driving consumer decisions, such as discounts, reviews, and payment preferences[cite: 2].

**The Objective:** Analyze a dataset of 3,900 customer purchases to identify trends, improve customer engagement, and optimize marketing and product strategies[cite: 2, 3].

## 📂 Repository Structure
* **`data/`**: Contains the raw dataset of 3,900 purchases across 18 demographic and transactional features[cite: 3].
* **`scripts/`**: 
  * `01_data_cleaning.ipynb`: Python (Pandas) script for EDA, handling missing review ratings, feature engineering, and database integration[cite: 3, 6].
  * `02_business_queries.sql`: SQL queries simulating business transactions, customer segmentation, and revenue analysis[cite: 3, 5].
* **`dashboards/`**: Power BI file (`.pbix`) containing the interactive Customer Behavior Dashboard[cite: 3].
* **`reports/`**: Neatly categorized folders containing the original business prompt, the comprehensive written analysis, and the stakeholder slide deck[cite: 2, 3, 7].

## 💡 Key Insights Uncovered
Through end-to-end data processing and visualization, the following key business drivers were identified:
* **Shipping Preferences Impact:** Customers utilizing Express Shipping spent an average of $65 per transaction, spending 12% more than Standard Shipping users ($58)[cite: 7].
* **The Power of Subscriptions:** Subscribers account for a massive 68% of the total revenue share and generally exhibit higher average spend[cite: 7]. 
* **Customer Segmentation:** The customer base currently consists of 50% New buyers, 35% Returning shoppers, and 15% Loyal customers (high-value)[cite: 7]. 
* **Strategic Discounting:** Identified a high-value segment of "Smart Shoppers" who utilize discounts but still manage to spend above the store average[cite: 7].

## 🎯 Business Recommendations
Based on the empirical data, I recommended the following strategic actions to stakeholders:
1. **Boost Subscriptions:** Promote exclusive benefits for subscribers to capitalize on their 68% revenue share[cite: 3, 7].
2. **Customer Loyalty Programs:** Implement targeted rewards to convert the 50% "New" buyer segment into "Returning" and "Loyal" tiers[cite: 3, 7].
3. **Targeted Marketing:** Focus marketing spend on high-revenue age groups and customers who prefer Express shipping[cite: 3, 7].
4. **Product Positioning:** Highlight top-rated products (e.g., Blouses and Dresses) in upcoming promotional campaigns to drive guaranteed satisfaction[cite: 3, 7].

## 🛠️ Tech Stack Used
* **Python**: Pandas, SQLAlchemy
* **SQL**: PostgreSQL / MS SQL Server
* **BI & Visualization**: Power BI
