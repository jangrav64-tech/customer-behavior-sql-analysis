📊 Customer Behavior & Engagement Analysis (SQL)
📌 Project Overview

This project analyzes customer behavior and engagement patterns using SQL on a real-world dataset. The objective is to derive actionable business insights such as customer distribution, engagement segmentation, and long-term user behavior to support data-driven decision making.

🎯 Business Objective

Organizations often struggle to understand customer engagement and retention patterns. This analysis helps identify:

Customer distribution across countries

Engagement level of users

High-value long-term customers

Behavioral segmentation for strategic targeting

🛠 Tools & Technologies

SQL (Google BigQuery)

Window Functions

Aggregations & Grouping

Data Segmentation Techniques

📂 Dataset

Customer Behavior Dataset

Key fields used:

Country

Gender

Age

Membership_Years

Login_Frequency

📊 Key Analysis Performed
1. Customer Distribution by Country

Identified regions with highest customer concentration.

2. Average Membership Duration

Measured customer loyalty and long-term retention trends.

3. Engagement Segmentation

Customers classified into:

High Engagement

Medium Engagement

Low Engagement

Based on login frequency behavior.

4. Top Engaged Customers

Identified most active users based on login frequency.

5. Customer Ranking (Window Function)

Ranked customers by engagement level using SQL window functions.

6. Engagement by Country

Compared average login frequency across different countries.

7. Engagement Segmentation with Percentage

Calculated percentage distribution of engagement groups.

8. Long-Term Customers

Identified customers with membership longer than 3 years.

🔍 Key Insights

Certain countries show significantly higher customer concentration.

High engagement users represent the core active customer base.

Long-term customers tend to have higher engagement frequency.

Engagement varies significantly across regions, indicating targeted strategy opportunities.

💼 Business Impact

This analysis enables businesses to:

Identify highly engaged users for retention strategies

Target low-engagement users for reactivation campaigns

Understand regional engagement behavior

Improve customer lifecycle management

📁 SQL File

customer_behavior_analysis.sql

Contains:

Aggregation queries

## 📊 Project Output

### SQL Result
![SQL Result](sql_result.png)

### Chart Visualization
![Chart](chart.png)

![Engagement Chart](engagement_chart.png)
![Average Login Chart](avg_login_chart.png)
