# 🛍️ Customer Shopping Behavior Analysis

## 📌 Project Overview
This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories.  
The objective is to uncover insights into spending patterns, customer segmentation, product preferences, subscription behavior, and revenue contribution to support business decision-making.

---

## 📊 Dataset Summary
- **Total Records:** 3,900
- **Total Columns:** 18
- **Key Features:**
  - Customer Demographics (Age, Gender, Location, Subscription Status)
  - Purchase Details (Item Purchased, Category, Purchase Amount, Season)
  - Shopping Behavior (Discount Applied, Previous Purchases, Review Rating, Shipping Type)

---

## 🧹 Data Cleaning & Preparation (Python)
- Loaded dataset using **Pandas**
- Handled 37 missing values in `review_rating` using median imputation
- Standardized column names (snake_case)
- Created new features:
  - `age_group`
  - `purchase_frequency_days`
- Removed redundant columns
- Loaded cleaned data into **PostgreSQL**

---

## 🛠 SQL Business Analysis

### 🔹 Key Business Questions Solved:

1. Revenue comparison by Gender
2. High-spending customers using discounts
3. Top 5 highest-rated products
4. Standard vs Express shipping spending comparison
5. Subscribers vs Non-subscribers revenue analysis
6. Products most dependent on discounts
7. Customer segmentation (New, Returning, Loyal)
8. Top 3 products per category
9. Repeat buyers vs subscription behavior
10. Revenue contribution by age group

---

## 📈 Key Insights

- Male customers generated significantly higher revenue than female customers.
- Express shipping customers spent slightly more on average.
- Loyal customers form the largest segment.
- Young Adults contributed the highest revenue among age groups.
- Non-subscribers generated more total revenue than subscribers.
- Some products (like Hats & Sneakers) heavily depend on discounts.

---

## 📊 Power BI Dashboard
Built an interactive dashboard including:
- Revenue by Category
- Revenue by Age Group
- Subscription Status Distribution
- Average Purchase Amount
- Average Review Rating

---

## 🧠 Business Recommendations

- Promote exclusive benefits to increase subscriptions
- Implement loyalty reward programs
- Re-evaluate discount-heavy product strategy
- Focus marketing on high-revenue age groups

---

## 💻 Tech Stack
- Python (Pandas, NumPy)
- PostgreSQL
- SQL (Advanced Queries, Window Functions, CTEs)
- Power BI

---

## 📎 Project Type
End-to-End Data Analytics Project (Data Cleaning → SQL Analysis → Dashboard → Business Recommendations)
