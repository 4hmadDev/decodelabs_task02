# Data Analysis

### Decode Labs | Data Science Internship — Task 2

## Project Overview

This project was completed as part of my internship at **Decode Labs**.

The main objective was to perform Exploratory Data Analysis (EDA) on an e-commerce dataset using Python. The analysis focuses on understanding data distributions, identifying patterns, calculating basic statistics, and detecting potential outliers.

## Dataset Information

The dataset contains **1,200 records and 14 columns** related to e-commerce orders.

Some of the important features include:

- OrderID
- Date
- CustomerID
- Product
- Quantity
- UnitPrice
- PaymentMethod
- OrderStatus
- ItemsInCart
- TotalPrice

## Tools & Technologies

- **Python** — Data analysis
- **Pandas** — Data manipulation and statistical analysis
- **Matplotlib** — Data visualization
- **Google Colab** — Development environment

## Tasks Performed

### 1. Data Exploration
- Examined the dataset using `head()`, `info()`, and `describe()`.
- Checked the dataset's structure and data types.
- Explored numerical and categorical features.

### 2. Descriptive Statistics
- Calculated mean, median, and unique order count.
- Analyzed order values and their distribution.

### 3. Data Visualization
Created visualizations including:
- Bar chart of most frequently ordered products
- Order status distribution chart
- Histogram of total order prices
- Boxplot for detecting potential outliers

### 4. Outlier Detection
- Used the Interquartile Range (IQR) method.
- Calculated Q1, Q3, and IQR.
- Identified 8 potential outliers in the TotalPrice column.

## Key Findings

| Metric | Result |
|---|---|
| Total Orders | 1,200 |
| Average Order Value | 1,053.97 |
| Median Order Value | 823.62 |
| Most Ordered Product | Printer |
| Least Ordered Product | Phone |
| Most Common Order Status | Cancelled |
| Potential Outliers | 8 |
| Highest Order Value | 3,456.40 |

### Additional Observations

- The order value distribution is right-skewed.
- Cancelled and returned orders account for approximately 41.4% of all orders.
- Most orders have relatively lower total prices compared with the highest-value orders.
- The IQR method identified unusually high order values, which may require further investigation.

## Project Files

- `Project_2_Exploratory_Data_Analysis.ipynb` — Google Colab notebook containing the analysis and visualizations.
- `cleaned_dataset.csv` — Dataset used for the analysis, if redistribution is permitted.

## Conclusion

This project helped me improve my understanding of Exploratory Data Analysis using Python, Pandas, and Matplotlib.

I gained practical experience in calculating descriptive statistics, visualizing distributions, identifying trends, and detecting potential outliers.

---

**Internship Organization:** Decode Labs  
**Project:** Task 2 — Exploratory Data Analysis  
**Author:** Ahmad Arfeen

**Connect with me:** [LinkedIn](https://www.linkedin.com/in/ahmadarfeen/)
