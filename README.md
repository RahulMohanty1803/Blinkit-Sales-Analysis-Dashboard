# Blinkit-Sales-Analysis-Dashboard-
To conduct a comprehensive analysis of Blinkit's sales performance, customer satisfaction &amp; outlet distribution to identify key insights and opportunities using various KPIs and visualization in Power Bi.

# Project Insights-

• Total sales is $1.20M.

• Average sales is $141

• Total no of item are 8523

• Average rating is 3.9

• Low fat product ordered more as compared to Regular fat product( Low fat- $776.32K & Regular fat- $ 425.36K )

• Fruits and Vegetable, Snack food, Household, Frozen Food & Dairy are top sale product contributing to 59.04% 

• Tier 3 Outlet type contributing to 39.29% of the total sales.

• Medium size outlet contributing to 42.27% of the total sales.


# DAX queries used-

1-- Avg_Rating = AVERAGE('BlinkIT Grocery Data'[Rating])

2-- Avg_Sales = AVERAGE('BlinkIT Grocery Data'[Sales])

3-- No_of_Items = COUNTROWS('BlinkIT Grocery Data')

4-- Total_Sales = SUM('BlinkIT Grocery Data'[Sales])
