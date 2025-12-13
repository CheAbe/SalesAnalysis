# Cofee Sales Analysis
This is a simple coffee sales analysis to showcase Python and Power BI skills.

1. Goal:
  To clean, analyze, and visualize the café’s sales data in order to extract insights that support operational optimization, revenue growth, and improved customer satisfaction, and to provide actionable recommendations based on the findings.

3. Key Questions
  - Which month delivers the highest revenue
  - Which coffee product has the highest sales volume
  - Which coffee product generates the most revenue
  - What the peak hours are by time of day and day of the week

3. Dataset Description
  The dataset was sourced from Kaggle and contains 3,547 café sales transactions from March 2024 to March 2025. It includes 11 columns that describe customer purchases.
  - hour_of_day – hour of purchase (0–23)
  - cash_type – payment method (cash/card)
  - money – transaction amount
  - coffee_name – type of coffee purchased
  - Time_of_day – categorized time (Morning, Afternoon, Night)
  - Weekday – day of the week
  - Month_name – month of purchase
  - Weekdaysort – numeric weekday order (1–7)
  - Monthsort – numeric month order (1–12)
  - Date – transaction date
  - Time – exact time of purchase

4. Methodology:
  4.1 Data Preparation
  To ensure the dataset was clean, consistent, and ready for analysis, I performed several preparation steps:
  - Used Python to simplify and speed up the data preparation process before importing the refined dataset into Power BI.
  - Reviewed the dataset to check for missing or null values.
    <p align="center">
    <img src="images/dataset review.png" width="700"/>
    </p>
    
  - Extracted the year from the date column to organize and segment the data by year.
  - Added a currency label (USD) to the transaction amount for clarity.

  4.2 Data Modeling
  A clean and organized data model was built in Power BI to support efficient analysis
  - Created measures using DAX to calculate KPIs such as monthly revenue, average order value, and total orders value.
  
  4.3 Data Visualization
  With the model in place, Power BI was used to design clear and insightful visualizations:
  - KPI cards to highlight key metrics at a glance.
  - Line charts to show revenue trends over time.
  - Bar charts to compare product popularity and revenue contribution.
  
  4.4 Insight Extraction
  The final step involved interpreting the visuals to identify meaningful patterns and trends:
  - Determined which month generated the highest revenue.
  - Identified the most popular coffee product by sales volume.
  - Highlighted which product contributed the most revenue.
  - Analyzed customer behavior to pinpoint peak hours of the day and week.

5. Conclusion
  - Total revenue: $112.25K from 3,547 orders with the average order value of $31.65 per transaction.
  - Oct 2024 shows the highest revenue of $13.89K.
  - American with milk is the top-selling product.
  - Latte is the top‑earning product.
  - Peak activity occurs midday(10 AM–4 PM) and on Mondays/Tuesdays.
  - Insights support better staffing, inventory, and promotional decision.

6. Recommendations
  - Continue promoting best‑selling products like Latte and Americano with Milk.
  - Increase staffing and inventory during peak hours (10 AM–4 PM).
  - Prepare for high‑revenue months with targeted promotions.
  - Introduce upselling strategies to raise average order value.









