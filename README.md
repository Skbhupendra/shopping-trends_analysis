# 🛍️ Shopping Trends Analysis

An exploratory data analysis (EDA) project focused on understanding customer purchasing patterns, product preferences, and demographic trends using Python.

---

## 📌 Project Overview

This project analyzes a retail shopping dataset to explore how customer demographics, product categories, spending behavior, shipping preferences, and promotional strategies relate to purchasing decisions.

The dataset contains 3,900 customer purchase records and 18 variables, making it suitable for descriptive analysis and business-focused insights.

---

## 🎯 Objectives

The current notebook focuses on:

- Understanding the age distribution of customers
- Identifying the most common purchasing patterns
- Checking dataset quality and consistency
- Exploring product categories and customer behavior
- Reviewing basic categorical distributions
- Building a foundation for further descriptive and predictive analysis

---

## 📊 Dataset

The project uses a shopping trends dataset with 3,900 rows and 18 columns.

### Dataset Features

| Feature | Description |
|--------|-------------|
| Customer ID | Unique customer identifier |
| Age | Customer age |
| Gender | Customer gender |
| Item Purchased | Product purchased |
| Category | Product category |
| Purchase Amount (USD) | Amount spent by customer |
| Location | Customer location |
| Size | Product size |
| Color | Product color |
| Season | Season of purchase |
| Review Rating | Customer rating |
| Subscription Status | Whether customer is subscribed |
| Shipping Type | Shipping method chosen |
| Discount Applied | Whether a discount was used |
| Promo Code Used | Whether a promo code was used |
| Previous Purchases | Number of previous purchases |
| Payment Method | Payment method used |
| Frequency of Purchases | Purchase frequency |

---

## 🔍 Data Quality Checks Performed

The notebook includes:

- Dataset shape inspection
- Column and dtype review
- Null-value analysis
- Unique-value extraction for categorical columns
- Initial descriptive statistics

### Current findings from the notebook

- Total rows: 3,900
- Total columns: 18
- Missing values: 0
- Average customer age: approximately 44.07 years

---

## 📈 Analysis Currently Included in the Notebook

The notebook currently covers:

### 1. Customer Demographics
- Age distribution
- Age frequency counts
- Mean age
- Age-group categorization

### 2. Dataset Structure
- Data shape
- Data types
- Column names
- Missing value check

### 3. Categorical Exploration
- Gender values
- Category values
- Size values
- Subscription status
- Shipping types
- Promo and discount status
- Payment methods

---

## 💡 Key Findings from the Current Analysis

Some notable findings observed in the notebook include:

- The dataset contains 3,900 purchase records.
- The average customer age is approximately 44.07 years.
- No missing values were detected in the dataset.
- The dataset includes four main product categories:
  - Clothing
  - Footwear
  - Outerwear
  - Accessories
- The most common gender values are Male and Female.
- The product size categories include S, M, L, and XL.
- Subscription status is binary: Yes or No.
- Shipping types include Express, Free Shipping, Next Day Air, Standard, 2-Day Shipping, and Store Pickup.
- Payment methods include Venmo, Cash, Credit Card, PayPal, Bank Transfer, and Debit Card.

These findings are descriptive and reflect the current sample of data rather than causal relationships.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Jupyter Notebook

---

## 📂 Repository Structure

```text
shopping-trends_analysis/
├── data/
│   └── shopping_trends.csv
├── notebooks/
│   └── Shopping_trends_analysis.ipynb
├── README.md
├── requirements.txt
└── .gitignore
