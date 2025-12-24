# 🛒 Market Basket Analysis & Customer Behavior Insights (Amazon)

## 📌 Overview
This project focuses on **Market Basket Analysis and Customer Behavior Analysis** using an Amazon customer survey dataset.  
The objective is to analyze customer purchasing patterns, segment customers, and generate actionable insights to improve **personalized recommendation systems**.

---

## 🎯 Objectives
- Analyze customer shopping behavior
- Identify frequently purchased product combinations
- Segment customers based on behavior and satisfaction
- Improve recommendation strategies using data-driven insights
- Reduce cart abandonment through behavioral analysis

---

## 📂 Dataset Information
- Total Records: 800
- Features: 24+
- Data Type: Survey + Transaction-style data

### Key Columns
- Demographics: Age, Gender
- Purchase Behavior: Purchase_Frequency, Purchase_Categories
- Recommendations & Reviews
- Cart & Browsing Behavior
- Customer Satisfaction

---

## 🧹 Task 1: Data Cleaning & Preparation
- Removed duplicate records
- Handled missing values (median for numeric, "Unknown" for categorical)
- Standardized text formats
- Converted frequency-based text to numeric values
- Fixed inconsistent and invalid entries

---

## 📊 Task 2: Exploratory Data Analysis
- Age and gender distribution analysis
- Purchase frequency trends
- Top product categories
- Browsing methods analysis
- Cart abandonment factors
- Customer satisfaction metrics

---

## 👥 Task 3: Customer Segmentation

### Rule-Based Segmentation
Customers classified into:
- Frequent Buyers
- Occasional Shoppers
- At-Risk Customers

Based on:
- Purchase frequency
- Shopping satisfaction

### K-Means Clustering
- Used Elbow Method & Silhouette Score
- Optimal clusters selected: 6
- Features used:
  - Purchase_Frequency_num
  - Shopping_Satisfaction
  - Customer_Reviews_Importance

---

## 🧠 Task 4: Recommendation & Review Insights
- Analyzed relationship between recommendation helpfulness and satisfaction
- Studied impact of review reliability on rating accuracy
- Segment-wise recommendation behavior analysis

---

## 🧺 Task 5: Market Basket Analysis
- Converted purchase categories into transaction format
- Applied One-Hot Encoding
- Generated Frequent Itemsets using Apriori Algorithm
- Created Association Rules using:
  - Support
  - Confidence
  - Lift

### Example Insight
Customers purchasing **Beauty & Personal Care** are more likely to purchase **Clothing & Fashion**.

---

## 📈 Task 6: Visualization & Reporting
- Bar charts for top categories
- Histograms for satisfaction levels
- Boxplots for recommendation impact
- Heatmaps for correlation analysis

---

## 🛠️ Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- MLxtend
- Jupyter Notebook

---

## 🚀 Key Learnings
- Market Basket Analysis helps in cross-selling
- Customer segmentation improves targeting
- Reviews and trust influence satisfaction
- Behavioral insights enhance recommendation quality

---

##👤 Author

Md Belal
Computer Science Student | Data Science & Analytics
Python | SQL | Machine Learning | Power BI
