# Automotive E-commerce Analytics Case Study

## Context

In the rapidly evolving automotive industry, online platforms have become pivotal in driving sales and customer engagement. For this case study, you will analyze data from different car sales platforms operated by the same car company in a single market.

## Objectives

Your task is to analyze the datasets provided and extract actionable insights that can help the company optimize its sales strategy across different platforms.

### Task 1: Data Analysis

Using the provided datasets, please perform the following analyses:

1. Describe the datasets and the eventual anomalies you find.
2. Which patterns do you find in the purchasing behavior of the customers?
3. Conduct a thorough exploratory data analysis to understand the datasets.
4. Perform customer segmentation to cluster users based on their interactions and purchasing behaviors on the different platforms.
5. Investigate the types of cars (e.g., electric, hybrid, diesel) preferred on each platform and how this correlates with the platform's sales performance and user satisfaction.
6. Open-ended exploration: you can explore the datasets further and propose additional analyses, modeling, visualizations, or insights.


## Dataset Descriptions (Metadata)

Below are descriptions of the datasets you will be working with:

#### Users Table (users.csv)
- `customer_id`: Unique identifier for the user.
- `user_first_name`: First name of the user.
- `user_last_name`: Last name of the user.
- `gender`: Gender of the user.
- `email`: Email address of the user.

#### Cars Table (cars.csv)
- `car_id`: Unique identifier for the car.
- `car_model`: Model of the car.
- `fuel_type`: Fuel type of the car.
- `release_date`: Date when the car was released.
- `price`: Base price of the car.

#### Sales Table (sales.csv)
- `transaction_id`: Unique identifier for the purchase.
- `customer_id`: Identifier for the user who made the purchase.
- `car_id`: Identifier for the car that was purchased.
- `platform`: Platform on which the purchase was made.
- `purchase_date`: Date when the purchase was made.
- `purchase_price`: Final price at which the car was sold after any discounts.
- `user_review`: An optional user review (as a score) given for the platform after each purchase.

#### Visit Table (visits.csv)
- `visit_id`: Unique identifier for the visit.
- `customer_id`: Identifier for the user who made the visit.
- `start_timestamp`: Timestamp when the visit started (website entry or dealership entry).
- `end_timestamp`: Timestamp when the visit ended.
- `visit_type`: Type of visit (e.g., purchasing, car configuration, testing). 
- `transaction_id`: purchase identifier for purchasing visits.

---

**NOTE: Data is taken from [@RandomAnass' Internship-Case-DS-2024 Repository](https://github.com/RandomAnass/Internship-Case-DS-2024).**

---
