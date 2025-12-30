

🛒 Customer Shopping Behavior Analysis

📌 Project Overview
This project analyzes customer shopping behavior using transactional data to uncover insights into spending patterns, customer segments, product performance, and subscription behavior.
The analysis combines Python, SQL (PostgreSQL), and Power BI to deliver end-to-end data analytics and business insights.



🎯 Objectives

* Understand customer spending patterns.

* Compare subscribers vs non-subscribers.

* Identify high-value customers and products

* Analyze revenue contribution by demographics

* Support data-driven business decisions




📂 Dataset Information

* Records: 3,900 customer purchases.

* Columns: 18.

* Data Includes:

      Customer demographics (Age, Gender, Location, Subscription Status)
   
      Purchase details (Category, Item Purchased, Purchase Amount)
   
      Shopping behavior (Discount, Promo Code, Frequency, Review Rating, Shipping Type)

   
* Missing Values: 37 values in Review Rating



🧰 Tools & Technologies

* Python – Pandas, NumPy (Data Cleaning & EDA)

* PostgreSQL – SQL queries & business analysis

* Power BI – Interactive dashboard & visualization

* GitHub – Version control & project documentation



🧹 Data Cleaning & Feature Engineering (Python)


* Loaded and explored dataset using Pandas

* Handled missing values by imputing median review ratings per category

* Renamed columns to snake_case for consistency

* Created new features:

    age_group (binned customer ages)

    purchase_frequency_days

* Identified and removed redundant column (promo_code_used)

* Exported cleaned data to PostgreSQL for SQL analysis



🗃️ SQL Analysis (PostgreSQL)

Key business questions answered using SQL:

1. Revenue comparison by Gender
2. High-spending customers who still use Discounts
3. Top 5 products by average review rating
4. Purchase amount comparison by Shipping Type
5. Spending comparison between Subscribers vs Non-Subscribers
6. Products most dependent on discounts
7. Customer segmentation: New, Returning, Loyal
8. Top 3 products in each category
9. Subscription likelihood of repeat buyers
10. Revenue contribution by Age Group



📊 Power BI 

An interactive Power BI dashboard was created to visualize:

* Revenue trends
* Customer segmentation
* Subscription analysis
* Product and category performance
* Age group contribution


📌 Dashboard highlights actionable insights for business stakeholders.

💡 Business Insights & Recommendations


📈 Boost subscriptions with exclusive offers


🎁 Introduce loyalty programs for repeat customers


⚖️ Optimize discount strategies to protect margins


⭐ Promote top-rated and high-selling products


🎯 Target marketing campaigns toward high-revenue age groups



📁 Project Structure
Customer-Shopping-Behavior-Analysis/


│

├── data/

│                   └── raw_dataset.csv


│
├── python/

│                    └── data_cleaning_and_eda.ipynb


│
├── sql/

│                    └── business_queries.sql

│
├── powerbi/ 

│                     └── dashboard.pbix


│
└── README.md

🚀 Conclusion
This project demonstrates a complete data analytics workflow, from raw data cleaning to SQL analysis and business-ready visualization.
It showcases strong skills in Python, SQL, Power BI, and analytical thinking, making it suitable for Data Analyst / Business Analyst roles.

I


