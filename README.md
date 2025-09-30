# Coffee-Shop-Sales-Data-Analysis
Coffee Shop Sales Data Analysis
# Project Objective
The primary objective of this project is to perform a comprehensive analysis of the coffee shop's sales data to derive actionable insights that can inform business strategy and optimize operations.
Specifically, the project aims to:
1.	**Identify key performance indicators (KPIs)** such as total sales, quantity sold, and average transaction metrics.
2.	**Uncover sales trends** across time, product categories, and outlets.
3.	**Determine customer demographics** and purchasing behavior to better target marketing efforts.
4.	**Evaluate product performance** and identify opportunities for waste reduction, particularly for pastry items.
5.	**Identify top-performing staff** and outlets to recognize success and replicate best practices.

# Data Cleaning and Preparation Process
1.	**Handling Missing Values**: Inspected all columns for missing entries. Based on the data dictionary and context, missing values were either imputed (e.g., using the mean/mode for numeric/categorical columns) or rows with irrecoverable missing data (like sales figures or dates) were removed.
2.	**Data Type Conversion:** Ensured all columns were assigned the correct data types. For example, dates were converted to a datetime format, numerical sales and quantity figures were set to appropriate numeric types, and categorical fields (like product group, outlet ID) were handled as strings or categories.
3.	**Standardizing Categorical Data:** Checked for and corrected inconsistencies in text fields (e.g., product names, staff names) by standardizing capitalization and fixing spelling errors to ensure accurate grouping and counting.
4.	**Data Validation:** Verified that calculated aggregates (e.g., total sales) matched expected totals to ensure the data was correctly loaded and transformed.

# Dashboard |  <a href="https://app.powerbi.com/groups/me/reports/f0385ec1-107f-4047-bbca-a2e5869b2c79/5c8574f3efe1ef5d8ac9?experience=power-bi">Link</a> 
<img width="682" height="383" alt="sales" src="https://github.com/user-attachments/assets/4f631914-fc04-4063-ae45-1bd769e6d3ce" />
<img width="681" height="385" alt="Product" src="https://github.com/user-attachments/assets/28fc383c-ae2e-4e4a-93d2-33f2b564b7a8" />
<img width="682" height="382" alt="Pastry" src="https://github.com/user-attachments/assets/5bca4e56-f465-41b4-a712-1475b28cfed0" />
<img width="682" height="384" alt="Customer" src="https://github.com/user-attachments/assets/fa2b59c1-478b-4563-a54b-67d9307fc0c3" />
<img width="682" height="383" alt="Outlet" src="https://github.com/user-attachments/assets/f3465b15-9065-4539-8abc-200542fd4e08" />




# Questions (KPIs)
-	What are the **total sales revenue** and **total quantity sold** in April 2019?
-	 Which is the **top-selling products** by revenue and by quantity?
-	 What is the **average transaction value**?
-	 Which outlets generated the **highest sales**?
-	 Who are the **top customers** by total spend?
-	 What is the **average spending per customer**?
-	 How do **customer demographics (gender, age groups, loyalty card holders)** impact spending?
-	 Which store have the **most customers**?
-	 What proportion of items sold were **promo items**?
-	 Which **product categories** contribute most to sales?
-	 What is the **average unit price** per product across transactions?
-	 Which **staff members** generate the highest sales?

# Project Insights
# Sales and Operations
-	**Total Sales:** The business generated **$233.64K** in total sales with **72K** units sold.
-	**Peak Transaction Time:** The period **9 AM to 11:30 AM** is identified as the clear peak selling time, suggesting a need for increased staffing and preparation during this window.
-	**Channel Performance:** Sales are almost equally split between **Instore (50.39%)** and **Online (49.61%)**, indicating a robust multi-channel business model.
-	**Top Staff:** **Britanni Jorden** is the top-selling staff member with **$27,516.04** in total sales, highlighting an individual whose sales strategies should be studied and shared.
# Product Performance and Waste
-	**Leading Product Group:** **Beverages** are the overwhelmingly most popular product group, accounting for **82.37%** of sales volume.
-	**Top Categories:** Within products, **Coffee (91K)** and **Tea (65K)** are the highest-selling categories by total sale.
-	**Pastry Waste:** A significant issue is the high rate of pastry waste, with **around 61% of pastries wasted than sold**. This points to a major opportunity for cost reduction and inventory optimization.
-	**Waste Outlet: Outlet ID 5** is responsible for the majority of the wasted pastries.
-	**Top Wasted Item: Ginger Snaps** are among the most wasted pastry items.
# Outlet Performance
-	**Total Outlets:** The business operates with **9** total outlets.
-	**Top Outlets by Sales: Outlet ID 8** ($79,528.25) and **Outlet ID 3** ($77,213.23) are the top two performing outlets by total sale.
-	**Best Sellers: Outlet ID 8** is the best seller for both** Coffee & others (24,109 quantity)** and **Pastry (1,077 quantity)**.
-	**Customer Count: Outlet ID 5** has the most customers, despite its lower sales rank, which may indicate a smaller average transaction size or a high number of loyalty-card holders.
# Customer Analysis
- **Gender: Men** are the shop's regular customers with **39,911** orders compared to women.
-	**Customer Generation: Baby Boomers** are the generation that places the most orders **(37,506)**, indicating they are the primary target demographic.
-	**Customer Growth:** The number of new customers has been declining since 2017 **(42,911)** to 2019 **(3,260)**, suggesting a potential need for stronger customer acquisition strategies.
-	**Top Customer: Kelly Key** is the top customer with an impressive **$119,312.72** in total sales.

# Conclusion and Recommendations
1.	**Reduce Pastry Waste:** Implement tighter inventory management and ordering protocols for pastries, focusing on **Outlet ID 5** and the **Ginger Snaps** product. Consider dynamic pricing or smaller batch production late in the day to minimize the **61% waste rate**.
2.	**Optimize Staffing:** Ensure adequate staffing during the **9 AM to 11:30 AM** peak period to maximize sales and customer satisfaction.
3.	**Leverage Top Performers:** Study the sales techniques of **Britanni Jorden** and the operational efficiency of **Outlet ID 8** and apply those best practices across other outlets.
4.	**Address Customer Acquisition:** Investigate the sharp decline in new customers since 2017 to understand the cause and develop targeted campaigns to attract new demographics, while continuing to cater to the loyal **Baby Boomer** base.
5.	**Investigate Outlet 5:** Determine why **Outlet ID 5** has the most customers but not the highest sales. This could indicate opportunities to increase the average transaction value through upselling or promotional bundles.




