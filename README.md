# Customer_Behavior_Analysis_Python-SQL-Tableau 07.12.25
This is a complete project on customer behavior analysis solving multiple real world problem solved with the help of tools like SQL, Python and Power BI

# Customer Shopping Behavior Analysis

Analyzes 3,900 customer transactions to uncover spending patterns, segmentation, and business insights using Python, SQL (PostgreSQL), and Power BI.

## 📊 Project Overview
Examines transactional data across product categories to reveal customer spending patterns, segments, product preferences, and subscription behaviors for strategic decision-making. 

## 📁 Dataset Rows: 3,900 | Columns: 18
**Key Features:**
- **Demographics**: Age, Gender, Location, Subscription Status
- **Purchases**: Item, Category, Amount, Season, Size, Color
- **Behavior**: Discounts, Previous Purchases, Frequency, Ratings, Shipping

**Data Quality**: 37 missing Review Rating values (imputed by category median) 

## 🛠️ Tech Stack
- **Python** (pandas): EDA & Data Prep
- **PostgreSQL**: Business Analytics Queries
- **Power BI**: Interactive Dashboard

## 🔍 Analysis Workflow

### Python EDA
Data Loading → pandas.read_csv()

Exploration → df.info() & df.describe()

Missing Data → Category-wise median imputation

Standardization → snake_case columns

Feature Engineering → agegroup, purchasefrequencydays

Consistency → Drop redundant promocodeused column

[file:1]

### SQL Business Queries (PostgreSQL)
1. Revenue by Gender
2. High-Spending Discount Users
3. Top 5 Products by Rating
4. Shipping Type Analysis
5. Subscriber vs Non-Subscriber Spend
6. Discount-Dependent Products
7. Customer Segmentation (New/Returning/Loyal)
8. Top 3 Products per Category
9. Repeat Buyer Subscription Patterns
10. Revenue by Age Group 

## 📈 Power BI Dashboard
Interactive visualizations of all key insights and business metrics.

## 💡 Business Recommendations
- 🎯 **Boost Subscriptions**: Exclusive subscriber benefits
- 🏆 **Loyalty Programs**: Reward repeat buyers
- ⚖️ **Discount Policy**: Balance volume vs margins
- 🚀 **Product Focus**: Promote top-rated bestsellers
- 🎨 **Targeted Marketing**: High-revenue age groups + express shipping
- 🌞 **Seasonal Strategy**: Summer discount campaigns
- ⭐ **Rating Improvement**: Maximize review participation




