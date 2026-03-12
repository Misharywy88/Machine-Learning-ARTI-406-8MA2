# Superstore Sales Dataset 🛒📊

| | |
|---|---|
| **Kaggle Link** | [Superstore Sales Dataset](https://www.kaggle.com/datasets/bhanupratapbiswas/superstore-sales) |
| **My Repo** | [Machine-Learning-ARTI-406-8MA2/Assignment 2](https://github.com/Misharywy88/Machine-Learning-ARTI-406-8MA2/tree/main/Assignment%202) |
| **File** | `Super_Store.csv` |
| **Rows** | ~9,800 transactions |
| **Columns** | 18 |
| **Time Period** | 2015–2018 |
| **Location** | United States |

## 📋 Column Details

| Column | Description |
|--------|-------------|
| `Row_ID` | Just a number for each row |
| `Order_ID` | Order reference number |
| `Order_Date` | When they bought it |
| `Ship_Date` | When it shipped |
| `Ship_Mode` | Shipping type (Standard Class, Second Class, etc.) |
| `Customer_ID` | Customer code |
| `Customer_Name` | Customer name |
| `Segment` | Consumer, Corporate, or Home Office |
| `Country` | All USA |
| `City` | City where delivered |
| `State` | State |
| `Postal_Code` | ZIP code |
| `Region` | Central, East, South, or West |
| `Product_ID` | Product code |
| `Category` | Furniture, Office Supplies, or Technology |
| `Sub_Category` | More specific product type (Chairs, Phones, Paper, etc.) |
| `Product_Name` | Full product description |
| `Sales` | How much it cost (what I might try to predict) |

## 🚀 Quick Start

```python
import pandas as pd
df = pd.read_csv('Super_Store.csv')
print(df.head())
print(df.info())
```

## 🔗 Link to my repo
https://github.com/Misharywy88/Machine-Learning-ARTI-406-8MA2/tree/main/Assignment%202

