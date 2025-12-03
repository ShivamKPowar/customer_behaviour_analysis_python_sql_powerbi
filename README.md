# Customer Shopping Behavior - Analysis and Dashboard
_A data-driven analysis of customer shopping behavior using Python, SQL, and Power BI to uncover key purchasing patterns and business insights._

---
## Table of Contents
- <a href="#overview">Overview</a>
- <a href="#business-problem">Business Problem</a>
- <a href="#dataset">Dataset</a>
- <a href="#tools-&-technologies">Tools & Technologies</a>
- <a href="#data-cleaning-&-preparation">Data Cleaning & Preparation</a>
- <a href="#data-analysis-using-sql">Data Analysis using SQL</a>
- <a href="#dashboard">Dashboard</a>

---
<h2><a class="anchor" id="overview"></a>Overview</h2>

This project analyzes customer shopping behavior to identify spending patterns, product performances, discount impact, and demographic trends. It combines data cleaning, exploratory analysis, and feature engineering in Python; tructured business queries in SQL for deeper insight; and an interactive Power BI dashboard to present clear, actionable findings for data-driven decision-making.

---
<h2><a class="anchor" id="business-problem"></a>Business Problem</h2>

- The business requires a clear understanding of how distinct customer segments interact with products and make purchase decisions.
- It is essential to identify the key drivers influencing customer spending behavior.
- The organization needs insight into which products, discount strategies, and behavioral patterns contribute most significantly to overall revenue.

---
<h2><a class="anchor" id="dataset"></a>Dataset</h2>
- The dataset consists of 3,900 customer transactions
- It includes following key features:
    - Customer Demographics: Age, Gender, Location, Subscription status.
    - Purchase Details: Item Purchased, Category, Purchase Amount, Season, Size, Color. 
    - Shopping Behavior: Discount Applied, Promo Code Used, Previous Purchases, Frequency 
of Purchases, Review Rating, Shipping Types.

---
<h2><a class="anchor" id="tools-&-technologies"></a>Tools & Technologies</h2>
- Python
- SQL
- Power BI
- Gitub

---
<h2><a class="anchor" id="data-cleaning-&-preparation"></a>Data Cleaning and Preparatiom</h2>
- Handling Missing Values: Identified null entries and addressed missing values in the review_rating column by imputing the median rating within each product category to preserve segment-level accuracy.
- Column Standerdization: Reanmed all column headers to snake case to ensure consistent formatting, redability, and ease of referance across the analysis.
- Feature Engineering:
    - Created an age_group feature by binning customer ages into defined demographic ranges.
    - Developed purchase_frequency_days by converting textual purchase intervals (e.g., Weekly, Quarterly, Annually) into standardized numeric values measured in days.
- Data Consistency Check: Identified redundancy between discount_applied and promo_code_used and removed the latter to avoid duplication.
- Database Integration: Connected the cleaned dataset to PostgreSQL and loaded it into a structured database table to enable advanced SQL-based analysis and business querying.

---
<h2><a class="anchor" id="data-analysis-usnig-sql"></a>Data Analysis using SQL</h2>
Conducted structured analysis in PostgreSQL to address key business questions and extract actionable insights.