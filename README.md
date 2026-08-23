# Customer Shopping Behaviour Analysis

## 📌 About the Project

Customer Shopping Behaviour Analysis is a data analytics project that analyzes customer purchase transactions to understand shopping patterns, customer segments, product preferences, discounts, subscriptions, and revenue trends.

The project uses **3,900 customer purchase records and 18 features** to generate meaningful business insights and support data-driven decision making.

## 🎯 Objectives

- Analyze customer purchasing behaviour
- Identify high-value and loyal customers
- Understand product preferences
- Analyze customer subscription behaviour
- Study the impact of discounts on purchases
- Compare revenue across customer groups
- Identify top-performing products and categories
- Build an interactive dashboard for business insights

## 📊 Dataset

The dataset contains **3,900 rows and 18 columns**.

### Main Data Categories

- Customer demographics
- Purchase information
- Product categories
- Purchase amount
- Subscription status
- Discount usage
- Previous purchases
- Purchase frequency
- Review ratings
- Shipping type
- Season, size, colour, and location

There were **37 missing values in the Review Rating column**, which were handled during data cleaning.

## 🐍 Data Cleaning & Preparation

Python and Pandas were used to prepare the dataset.

The following steps were performed:

- Loaded the dataset using Pandas
- Explored the dataset using `info()` and `describe()`
- Checked and handled missing values
- Imputed missing review ratings using category-wise median ratings
- Standardized column names using snake_case
- Created `age_group`
- Created `purchase_frequency_days`
- Checked redundant columns
- Removed `promo_code_used`
- Loaded the cleaned data into PostgreSQL

## 🗄️ SQL Business Analysis

PostgreSQL was used to perform business-oriented SQL analysis.

### Key Analysis Performed

1. Revenue analysis by gender
2. Identification of high-spending discount users
3. Top 5 products based on average rating
4. Comparison of Standard and Express shipping
5. Subscriber vs. non-subscriber analysis
6. Identification of discount-dependent products
7. Customer segmentation
8. Top 3 products within each category
9. Repeat buyers and subscription analysis
10. Revenue analysis by age group

## 👥 Customer Segmentation

Customers were classified into three segments based on their purchase history:

- **New Customers**
- **Returning Customers**
- **Loyal Customers**

The analysis identified **3,116 loyal customers, 701 returning customers, and 83 new customers**.

## ⭐ Product Insights

The SQL analysis identified the top-rated products based on average review ratings.

| Product | Average Rating |
|---|---:|
| Gloves | 3.86 |
| Sandals | 3.84 |
| Boots | 3.82 |
| Hat | 3.80 |
| Skirt | 3.78 |

## 📈 Power BI Dashboard

An interactive **Power BI dashboard** was created to visualize the results.

### Dashboard Features

- Average Purchase Amount
- Average Review Rating
- Number of Customers
- Revenue by Category
- Sales by Category
- Revenue by Age Group
- Sales by Age Group
- Subscription Status
- Gender Filter
- Category Filter
- Shipping Type Filter

The dashboard provides an easy way to explore customer behaviour and business performance.

## 🛠️ Technologies Used

- **Python**
- **Pandas**
- **PostgreSQL**
- **SQL**
- **Power BI**

## 🔄 Project Workflow

```text
Customer Transaction Dataset
          ↓
    Python + Pandas
          ↓
   Data Cleaning
          ↓
 Feature Engineering
          ↓
     PostgreSQL
          ↓
    SQL Analysis
          ↓
    Power BI Dashboard
          ↓
 Business Insights
          ↓
Recommendations
