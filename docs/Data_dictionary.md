# Data Dictionary

| Column                   | Data Type   | Description                                                                    |
| ------------------------ | ----------- | ------------------------------------------------------------------------------ |
| `Customer ID`            | Integer     | Unique identifier assigned to each customer.                                   |
| `Age`                    | Integer     | Age of the customer.                                                           |
| `Gender`                 | Categorical | Gender of the customer.                                                        |
| `Item Purchased`         | Categorical | Specific product purchased by the customer.                                    |
| `Category`               | Categorical | Product category, such as Clothing, Footwear, Outerwear, or Accessories.       |
| `Purchase Amount (USD)`  | Integer     | Amount spent on the purchase in US dollars.                                    |
| `Location`               | Categorical | Customer's location/state.                                                     |
| `Size`                   | Categorical | Size of the purchased product.                                                 |
| `Color`                  | Categorical | Color of the purchased product.                                                |
| `Season`                 | Categorical | Season associated with the purchase.                                           |
| `Review Rating`          | Float       | Customer rating associated with the purchased product.                         |
| `Subscription Status`    | Categorical | Indicates whether the customer has an active subscription status (`Yes`/`No`). |
| `Shipping Type`          | Categorical | Shipping method selected for the purchase.                                     |
| `Discount Applied`       | Categorical | Indicates whether a discount was applied (`Yes`/`No`).                         |
| `Promo Code Used`        | Categorical | Indicates whether a promotional code was used (`Yes`/`No`).                    |
| `Previous Purchases`     | Integer     | Number of previous purchases made by the customer.                             |
| `Payment Method`         | Categorical | Payment method used for the purchase.                                          |
| `Frequency of Purchases` | Categorical | Frequency at which the customer makes purchases.                               |

## Categorical Values Observed

### Gender

* Male
* Female

### Category

* Clothing
* Footwear
* Outerwear
* Accessories

### Size

* S
* M
* L
* XL

### Subscription Status

* Yes
* No

### Shipping Type

* Express
* Free Shipping
* Next Day Air
* Standard
* 2-Day Shipping
* Store Pickup

### Discount Applied

* Yes
* No

### Promo Code Used

* Yes
* No

### Payment Method

* Venmo
* Cash
* Credit Card
* PayPal
* Bank Transfer
* Debit Card
