🛒 Market Basket Analysis & Customer Behavior Insights (Amazon)
📌 Project Overview

This project performs Market Basket Analysis and Customer Behavior Analysis using an Amazon customer survey dataset.
The goal is to understand customer purchase patterns, shopping behavior, segmentation, and generate actionable insights to improve recommendation systems and business decisions.

The project combines:

Data Cleaning & Preparation

Exploratory Data Analysis (EDA)

Customer Segmentation (Rule-based + K-Means)

Market Basket Analysis using Apriori Algorithm

Visualization & Reporting

🧠 Business Objectives

Identify frequently purchased product combinations

Understand customer shopping behavior & satisfaction

Segment customers into meaningful groups

Improve personalized recommendation strategies

Extract insights to reduce cart abandonment

🗂️ Dataset Description

Rows: 800

Columns: 24+

Data Type: Customer survey & transaction-style data

Key Features:

Demographics: Age, Gender

Purchase behavior: Purchase_Frequency, Purchase_Categories

Recommendation usage & satisfaction

Reviews & ratings

Cart behavior & browsing patterns

🧹 Task 1: Data Cleaning & Preparation

✔ Removed duplicates
✔ Handled missing values (median for numeric, "Unknown" for categorical)
✔ Standardized text formats
✔ Converted frequency-based text into numeric scales
✔ Fixed inconsistent survey responses (invalid ages, formats)

📊 Task 2: Descriptive Behavior Analysis

Age & gender distribution

Purchase frequency trends

Top product categories

Browsing methods analysis

Cart abandonment factors

Customer satisfaction statistics

📌 Key Insight:
Clothing, Home & Kitchen, Beauty & Personal Care are the most popular categories.

👥 Task 3: Customer Segmentation & Profiling
🔹 Rule-Based Segmentation

Customers classified into:

Frequent Buyers

Occasional Shoppers

At-Risk Customers

Based on:

Purchase frequency

Shopping satisfaction

🔹 K-Means Clustering

Used Elbow Method & Silhouette Score

Optimal clusters: 6

Features used:

Purchase Frequency

Shopping Satisfaction

Review Importance

📌 Created detailed customer profiles per segment.

🔍 Task 4: Recommendation & Review Insights

Correlation between recommendation helpfulness & satisfaction

Impact of review reliability on rating accuracy

Segment-wise recommendation behavior analysis

📌 Key Insight:
Customers who trust recommendations and reviews show better engagement and satisfaction.

🧺 Task 5: Market Basket Analysis (Apriori)

Converted purchase categories into transaction format

Applied One-Hot Encoding

Generated Frequent Itemsets

Built Association Rules using:

Support

Confidence

Lift

📌 Example Insight:
Customers buying Beauty & Personal Care are likely to also buy Clothing & Fashion.

📈 Task 6: Visualization & Reporting

Visualizations include:

Bar charts (top categories, browsing frequency)

Histograms (satisfaction levels)

Boxplots (recommendation vs satisfaction)

Heatmaps (correlation analysis)

📽️ Video Presentation:
👉 Loom Video Link included in notebook

🛠️ Tools & Technologies Used

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

MLxtend (Apriori, Association Rules)

Jupyter Notebook

🚀 Key Takeaways

Market Basket Analysis helps in cross-selling strategies

Customer segmentation enables targeted recommendations

Reviews & trust play a critical role in satisfaction

Behavioral data improves personalized shopping experience

📌 How to Run the Project
pip install pandas numpy matplotlib seaborn scikit-learn mlxtend


Open and run:

Market Basket Analysis with Python- Amazon.ipynb

👤 Author

Md Belal
Computer Science Student | Data Analytics & Data Science
📊 Python | SQL | Machine Learning | Power BI
