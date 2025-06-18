# Exercise | Prjocet Data Analyst With Excel - Retail Store Sales

## Data Cleaning
1. Standardizing date format
2. Removing duplicates
3. Handling missing values (by imputing the mean)

## Data Processing
1. Created Year, Month, and Day column from Order Date column
2. Created Delivery Time column (calculated by subtracting Order Date from Delivered Date)
3. Created Total Cost, Net Profit, and Sales Revenue columns

## Data Analyst
Skenario: Whether there is relationship between delivery time and order status (Completed | Returned)
H0: Delivery time does not affect whether an order is returned.
H1: Orders with longer delivery times are more likely to be returned.

Based on the results of the t-Test: Two-Sample Assuming Unequal Variances, the p-value (P(T<=t) two-tail) was found to be less than the alpha level of 0.05. 
Therefore, the alternative hypothesis (H1) is accepted. This indicates a significant difference between the average delivery time of returned orders and completed orders.
In other words, delivery time has an impact on order status.

As an insight, it is recommended to monitor orders with a delivery time of more than 7 days. This is intended to reduce the risk of product returns due to delivery delays.

## Data Collection
Created data entry from

## Data Visualization


