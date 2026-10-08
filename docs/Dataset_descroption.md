# Dataset Description

## Overview

The dataset contains customer shopping information used to analyze purchasing behavior, customer demographics, product preferences, and transaction-related patterns.

The dataset contains **3,900 records and 18 columns**. Each row represents a customer purchase record, while the columns contain information about the customer, purchased product, transaction amount, shopping preferences, and purchasing behavior.

The dataset is loaded in the analysis notebook from a CSV file named `shopping_trends.csv`.

## Dataset Dimensions

* **Rows:** 3,900
* **Columns:** 18
* **Numerical columns:** 5
* **Categorical/text columns:** 13
* **Missing values:** None identified during the notebook's missing-value check.

## Main Areas Covered

The dataset provides information about:

* Customer demographics
* Products purchased
* Product categories
* Purchase amounts
* Customer locations
* Product sizes and colors
* Seasonal purchasing
* Customer review ratings
* Subscription status
* Shipping preferences
* Discounts and promotional codes
* Previous purchase history
* Payment methods
* Purchase frequency

## Dataset Fields

The original dataset contains the following 18 fields:

1. Customer ID
2. Age
3. Gender
4. Item Purchased
5. Category
6. Purchase Amount (USD)
7. Location
8. Size
9. Color
10. Season
11. Review Rating
12. Subscription Status
13. Shipping Type
14. Discount Applied
15. Promo Code Used
16. Previous Purchases
17. Payment Method
18. Frequency of Purchases

## Data Quality

The notebook performs basic data-quality checks including:

* Dataset shape
* Column names
* Data types
* Dataset information
* Missing-value detection
* Unique-value inspection for selected categorical variables

The missing-value check found **0 missing values across the dataset**.

## Important Note

The notebook does not document the original external source, collection methodology, sampling methodology, or licensing information for `shopping_trends.csv`. These details should only be added if they can be verified from the original dataset source.

## Analytical Purpose

The dataset is used to investigate questions such as:

* What is the distribution of customer ages?
* How does average purchase amount vary by product category?
* Which gender has the highest number of purchases?
* Which products are most commonly purchased?
* How does purchasing vary by season?
* How do review ratings differ across categories?
* How does subscription status relate to purchasing?
* Which payment methods are used by customers?
* Do promo codes and discounts relate to purchasing behavior?
* How does purchasing frequency vary across age groups?
* Is there a relationship between numerical variables such as age, purchase amount, review rating, and previous purchases?
* Which shipping types are preferred across product categories?
* Which colors are most frequently purchased?
* How does purchasing behavior vary by location?
