# Superstore Sales Dataset 🛒📊

[![Kaggle](https://img.shields.io/badge/Kaggle-Dataset-blue?logo=kaggle&logoColor=white)](https://www.kaggle.com/datasets/bhanupratapbiswas/superstore-sales)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)
![Python](https://img.shields.io/badge/Python-EDA%20%7C%20Analysis-green?logo=python&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-Power%20BI%20%7C%20Tableau-orange?logo=microsoft-excel&logoColor=white)

**Superstore Sales** is a classic, widely-used retail dataset perfect for **Exploratory Data Analysis (EDA)**, **business intelligence**, **data visualization**, **dashboard creation**, and **predictive modeling practice**.

It simulates sales transactions of a fictional **US-based superstore** selling furniture, office supplies, and technology products.

## 📌 Dataset Overview

- **Source**: [Kaggle – Superstore Sales by Bhanupratap Biswas](https://www.kaggle.com/datasets/bhanupratapbiswas/superstore-sales)
- **File**: `superstore_sales.csv` (or similar name after download)
- **Rows**: ≈ 9,800–10,000 transactions
- **Columns**: 18–21 (depending on version)
- **Time period**: Orders mainly from 2015–2018
- **Geography**: United States (49 states + District of Columbia)
- **License**: Public / CC0 (free to use for learning, analysis, portfolios)

### Key Business Questions You Can Answer

- Which **category/sub-category** generates the most/least revenue & profit?
- Which **region / state / city** performs best or worst?
- How do **customer segments** (Consumer, Corporate, Home Office) differ in behavior?
- What is the impact of **discounts** on profit?
- Which products should be prioritized or discontinued?
- How does **shipping mode** affect delivery time and customer satisfaction?

## 📋 Column Descriptions

| Column Name       | Data Type    | Description                                                                 |
|-------------------|--------------|-----------------------------------------------------------------------------|
| Row ID            | Integer      | Unique row identifier                                                       |
| Order ID          | String       | Unique order identifier                                                     |
| Order Date        | Date         | Date when the order was placed                                              |
| Ship Date         | Date         | Date when the order was shipped                                             |
| Ship Mode         | Category     | Shipping method (Standard Class, Second Class, First Class, Same Day)      |
| Customer ID       | String       | Unique customer identifier                                                  |
| Customer Name     | String       | Full name of the customer                                                   |
| Segment           | Category     | Customer type (Consumer, Corporate, Home Office)                            |
| Country           | String       | Country (always United States in this dataset)                              |
| City              | String       | City where the customer is located                                          |
| State             | String       | US State                                                                    |
| Postal Code       | Integer/String | ZIP code                                                                   |
| Region            | Category     | US Region (West, East, South, Central)                                      |
| Product ID        | String       | Unique product identifier                                                   |
| Category          | Category     | Main product category (Furniture, Office Supplies, Technology)             |
| Sub-Category      | Category     | Sub-product category (e.g., Chairs, Phones, Binders, Storage...)           |
| Product Name      | String       | Detailed product name                                                       |
| Sales             | Float        | Revenue from the transaction (USD)                                          |
| Quantity          | Integer      | Number of units sold                                                        |
| Discount          | Float        | Discount rate applied (0–0.8)                                               |
| Profit            | Float        | Profit after costs & discount (can be negative)                             |

> **Note**: Some versions include extra columns or slight name variations — check your downloaded file.

## 🚀 Getting Started

1. **Download the dataset** from Kaggle:  
   https://www.kaggle.com/datasets/bhanupratapbiswas/superstore-sales

2. **Clone this repository**:
   ```bash
   git clone https://github.com/YOUR-USERNAME/superstore-sales-analysis.git
   cd superstore-sales-analysis