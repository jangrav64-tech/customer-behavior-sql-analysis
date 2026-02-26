## Project Architecture

The project follows a structured analytics workflow:

1. **Data Source**
   - Raw customer behavior dataset imported into Google BigQuery

2. **Data Processing**
   - Data cleaning and transformation using SQL
   - Derived fields for engagement segmentation
   - Aggregations and grouping for behavioral analysis

3. **Analytics Layer**
   - Customer distribution analysis
   - Engagement segmentation (High / Medium / Low)
   - Ranking using Window Functions
   - Long-term customer identification
   - Regional engagement comparison

4. **Visualization**
   - Query outputs visualized using charts and tables
   - Screenshots added for result interpretation

5. **Business Insights**
   - Engagement-driven customer behavior understanding
   - Identification of high-value and low-engagement users
   - Regional performance comparison

---

## 📈 Analytical Approach

The analysis was performed using:

- Aggregation & Grouping  
- Window Functions (ROW_NUMBER)  
- Behavioral Segmentation  
- Percentage Distribution using analytic functions  
- Business-driven interpretation of data  

This approach ensures both **technical depth** and **business relevance**.

---

---

## 📊 Project Visualization

<h2>🖥 Executive Dashboard (Click to Open Live)</h2>

<a href="https://lookerstudio.google.com/reporting/5278ddb2-9b8a-4d2d-a904-a2684f4183cd" target="_blank">
  <img src="dashboard.png" alt="Executive Dashboard" width="800"/>
</a>

These visualizations represent the analytical output derived from SQL queries and help interpret customer engagement behavior effectively.

---
