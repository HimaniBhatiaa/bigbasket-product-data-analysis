# 🛒 BigBasket Product Data Analysis

## 📌 Project Overview
The BigBasket Product Data Analysis project performs Exploratory Data Analysis (EDA) on an e-commerce product dataset to understand pricing behavior, discount trends, and category performance.

The project demonstrates a complete data analytics workflow including data cleaning, missing value handling, outlier detection, feature engineering, and visualization using Python.

---

## 🎯 Business Objective
E-commerce platforms handle thousands of products with varying prices and discounts. This project helps to:

- Identify pricing inconsistencies
- Understand discount effectiveness
- Detect abnormal pricing values
- Compare category-level pricing performance
- Generate actionable business insights

---

## 📂 Dataset Description

| Column | Description |
|--------|-------------|
| index | Product identifier |
| product | Product name |
| category | Product category |
| market_price | Original price |
| sale_price | Discounted price |
| rating | Customer rating |
| Discount | Calculated discount |

---

## ⚙️ Project Workflow

### Data Loading
- Dataset imported using Pandas
- Invalid rows handled using `on_bad_lines='skip'`

### Data Understanding
- Used `head()` for preview
- Used `info()` for structure
- Used `describe()` for statistical summary

### Feature Engineering
Created Discount column using pricing information.

### Missing Value Handling
- Checked missing values using `isnull().sum()`
- Applied mean imputation where required

### Outlier Detection
Used IQR method on:
- index
- sale_price
- market_price

### Data Visualization
Created:
- Histogram (price distribution)
- Boxplot (outlier detection)
- Scatter plot (market vs sale price)
- Category-wise bar chart
- Correlation heatmap

---

## 📊 Key Insights
- Strong relationship between market price and sale price
- Pricing varies significantly across categories
- Discounts influence final selling prices
- Outliers exist in pricing data

---

## 🛠️ Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---
## 💼 Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Data Cleaning & Preprocessing
- Outlier Detection (IQR Method)
- Data Visualization
- Business Insight Generation

---

## 🚀 Future Improvements

- Tableau Dashboard Integration
- Machine Learning Price Prediction
- Interactive Analytics Dashboard


## 📁 Project Structure
bigbasket-product-data-analysis/
│
├── Big Basket mini project.ipynb
├── README.md
└── dataset.csv

## 🔗 Project Repository
👉 [View Project on GitHub](https://github.com/HimaniBhatiaa/bigbasket-product-data-analysis)


## 👩‍💻 Author & Contact

**Himani Bhatia**  
Data Analyst passionate about Data Visualization, Python Analytics, and Business Insights.

- 🔗 LinkedIn: https://www.linkedin.com/in/himani-bhatia18/
- 💻 GitHub: https://github.com/HimaniBhatiaa




