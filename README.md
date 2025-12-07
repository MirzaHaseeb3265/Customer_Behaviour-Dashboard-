# 🛍️ Customer Shopping Behavior Analysis

## 📌 Project Overview
This project analyzes customer shopping behavior using transactional data from **3,900 purchases** across multiple product categories. The objective is to extract insights on spending patterns, customer segmentation, product preferences, and subscription behavior to support strategic business decisions.

---

## 📊 Dataset Summary
- **Rows:** 3,900
- **Columns:** 18
- **Key Data Features:**
  - Customer demographics: Age, Gender, Location, Subscription Status
  - Purchase details: Item Purchased, Category, Purchase Amount, Season, Size, Color
  - Shopping behavior: Discount Applied, Promo Code Used, Previous Purchases, Frequency of Purchases, Review Rating, Shipping Type
- **Missing Data:** 37 missing values in the Review Rating column

---

### 🛠️ Feature Engineering
- Created **age_group** by binning ages
- Generated **purchase_frequency_days** from purchase history
- Validated redundancy between `discount_applied` and `promo_code_used` and removed the latter

### 🗄️ Database Integration
- Loaded cleaned DataFrame into the database for SQL-based business queries

---

## 🧮 Data Analysis Using SQL (MySQL)
Key business questions answered:
1. **Revenue by Gender** – Compared total revenue between male and female customers.
2. **High-Spending Discount Users** – Identified customers using discounts yet spending above average.
3. **Top 5 Products by Review Rating** – Highest-rated products.
4. **Shipping Type Comparison** – Standard vs. Express shipping purchase amounts.
5. **Subscribers vs. Non-Subscribers** – Compared spend and revenue contributions.
6. **Discount-Dependent Products** – Products with the highest discounted purchase percentages.
7. **Customer Segmentation** – Classified customers as New, Returning, or Loyal.
8. **Top 3 Products per Category** – Most purchased products by category.
9. **Repeat Buyers & Subscriptions** – Checked subscription likelihood for frequent buyers (>5 purchases).
10. **Revenue by Age Group** – Contribution of each age group to total revenue.

---

## 📊 Power BI Dashboard
An interactive dashboard was built using **Power BI**, visualizing:
- Revenue insights
- Customer segments
- Product performance
- Subscription behavior
- Shipping preferences

---

## 💡 Business Recommendations
- **Boost Subscriptions** – Promote exclusive subscriber perks.
- **Strengthen Loyalty Programs** – Reward repeat customers to convert them into "Loyal" buyers.
- **Review Discount Strategy** – Balance promotional discounts with profit margins.
- **Optimize Product Positioning** – Highlight top-rated and best-selling products.
- **Targeted Marketing** – Focus on high-revenue age groups and users preferring express shipping.

---

## 📬 Contact
haseebbaig990@gmail.com

