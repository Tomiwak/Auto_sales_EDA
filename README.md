# Auto Sales Data Analysis

## 📌 Overview
This project analyzes an auto sales dataset to uncover trends, patterns, and key insights about product sales, customer behavior, and order statuses. The dataset includes **2,747 records** with features like order details, product lines, countries, and deal sizes.

---

## 📂 Dataset
- **Source**: `Auto Sales data.csv`  
- **Rows**: 2,747  
- **Columns**: 20 (e.g., `ORDERNUMBER`, `QUANTITYORDERED`, `PRICEEACH`, `SALES`, `PRODUCTLINE`, `COUNTRY`, `DEALSIZE`)  
- **Time Period**: Orders from 2018 to 2020.

---

## 🔍 Analysis Steps
### 1. Data Preparation
- Loaded and inspected the dataset using `pandas`.
- Handled datetime conversion for `ORDERDATE`.
- Dropped irrelevant columns and checked for duplicates.

### 2. Exploratory Data Analysis (EDA)
- **Descriptive Statistics**: Analyzed sales distributions, order quantities, and pricing.
- **Categorical Variables**:  
  - Top product line: **Classic Cars**.  
  - Most orders were **Shipped**.  
  - Deal sizes: Medium > Small > Large.  
- **Geographic Trends**: USA had the highest sales volume.

### 3. Key Insights
- **Sales Performance**: Average sale amount was **$3,553**, with a wide range ($482–$14,082).  
- **Product Trends**: Motorcycles and Vintage Cars had higher price variability.  
- **Time Analysis**: Orders peaked in mid-2019 (see plots).

---

## 📊 Visualizations
- Bar plots for categorical variables (`STATUS`, `PRODUCTLINE`).  
- Histograms for numerical variables (`SALES`, `QUANTITYORDERED`).

---

## 🛠 Tools Used
- **Python Libraries**:  
  ```python
  pandas, numpy, matplotlib, seaborn
  ```
- **Data Cleaning**: Handled datetime formats and filtered columns.  
- **Visualization**: Generated plots to highlight trends.

---

## 🔑 Key Takeaways
1. **Classic Cars dominate sales**, suggesting a focus area for inventory.  
2. **Medium deals** are most common, but large deals drive revenue.  
3. **USA is the largest market**.  

---

## 📈 Next Steps
- **Bivariate Analysis**: Correlate `SALES` with `COUNTRY` or `DEALSIZE`.  
- **Time Series Forecasting**: Predict future sales trends.  
- **Customer Segmentation**: Cluster buyers by purchase behavior.
