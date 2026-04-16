# Customer-Behavior-Analysis
data analytics project showcasing customer behavior ana# Customer Shopping Behavior Analysis

## 📊 Project Overview
This project analyzes customer shopping behavior using transactional data from **3,900 purchases** across various product categories.  
The main objective is to uncover insights into spending patterns, customer segmentation, product performance, and subscription behavior to support data-driven business decisions.

---

## 📁 Dataset Summary
- **Rows:** 3,900  
- **Columns:** 18  

### Key Features:
- Customer Demographics: Age, Gender, Location, Subscription Status  
- Purchase Details: Item Purchased, Category, Purchase Amount, Season, Size, Color  
- Shopping Behavior: Discount Applied, Promo Code Used, Previous Purchases, Frequency of Purchases, Review Rating, Shipping Type  
- Missing Values: 37 missing values in **Review Rating**

---

## 🧹 Data Cleaning & Preprocessing (Python)

The dataset was cleaned and prepared using Python (Pandas):

- Imported dataset using `pandas`
- Explored structure using `df.info()` and `df.describe()`
- Handled missing values in **Review Rating** using median per category
- Standardized column names to `snake_case`
- Feature engineering:
  - Created `age_group` from customer age
  - Created `purchase_frequency_days`
- Checked redundancy between `discount_applied` and `promo_code_used`
- Dropped `promo_code_used` due to redundancy
- Loaded cleaned data into **PostgreSQL** for SQL analysis

---

## 🧮 SQL Data Analysis (Business Insights)

Performed analytical queries in PostgreSQL to answer key business questions:

1. Revenue comparison by gender  
2. High-spending customers using discounts  
3. Top 5 highest-rated products  
4. Shipping type impact on spending  
5. Subscribers vs non-subscribers revenue comparison  
6. Products most dependent on discounts  
7. Customer segmentation (New, Returning, Loyal)  
8. Top 3 products per category  
9. Repeat buyers vs subscription tendency  
10. Revenue distribution by age group  

---

## 📊 Power BI Dashboard
An interactive Power BI dashboard was built to visualize:
- Revenue trends
- Customer segmentation
- Product performance
- Subscription behavior
- Key business KPIs

---

## 💡 Business Recommendations

- **Increase Subscription Value**  
  Promote exclusive benefits to encourage more users to subscribe.

- **Customer Loyalty Programs**  
  Reward repeat customers to move them into the “Loyal” segment.

- **Optimize Discount Strategy**  
  Balance discount usage with profit margins to avoid revenue loss.

- **Product Promotion Strategy**  
  Focus marketing on top-rated and best-selling products.

- **Targeted Marketing Campaigns**  
  Prioritize high-revenue age groups and express shipping users.

---

## 🚀 Tools & Technologies
- Python (Pandas, NumPy)
- PostgreSQL
- SQL
- Power BI
- Data Visualization

---

## 📌 Author
Data Analytics Project – Customer Behavior Analysislysis using python, sql and power bi.
