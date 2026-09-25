# festival Sales data EDA using Python

An exploratory data analysis project focused on understanding customer purchasing behavior during the Diwali sales period. The project uses Python and data visualization techniques to identify customer demographics, purchasing patterns, popular product categories, and key sales trends.

## Project Overview

The objective of this project is to analyze Diwali sales data and extract meaningful business insights from customer and transaction information.

The analysis covers customer demographics, age groups, gender, marital status, location, occupation, product categories, order quantity, and sales amount.

The original dataset contains **11,251 records and 15 columns**. After removing two unrelated empty columns and rows containing missing sales amounts, the analysis uses **11,239 records across 13 columns**.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## Dataset

The dataset contains information about customers and their purchases.

Important columns include:

* `User_ID` – Unique customer identifier
* `Cust_name` – Customer name
* `Product_ID` – Product identifier
* `Gender` – Customer gender
* `Age Group` – Customer age category
* `Age` – Customer age
* `Marital_Status` – Marital status
* `State` – Customer state
* `Zone` – Geographic zone
* `Occupation` – Customer occupation
* `Product_Category` – Product category
* `Orders` – Number of orders
* `Amount` – Purchase amount

These columns are present in the cleaned dataset used for analysis.

## Data Cleaning

The following preprocessing steps were performed:

1. Imported the dataset using Pandas.
2. Checked the dataset shape and structure.
3. Inspected data types and missing values.
4. Removed the `Status` and `unnamed1` columns because they contained no useful data.
5. Identified 12 missing values in the `Amount` column.
6. Removed rows containing missing values.
7. Converted the `Amount` column from float to integer.
8. Performed descriptive statistical analysis.

The cleaned dataset contains 11,239 rows.

## Exploratory Data Analysis

The project analyzes sales from multiple perspectives, including:

### Customer Demographics

The analysis explores purchasing behavior based on:

* Gender
* Age
* Age Group
* Marital Status

The analysis particularly examines the `26-35` age group and compares purchasing behavior across genders.

### Geographic Analysis

Sales and order patterns are analyzed across different Indian states and geographic zones.

### Occupation Analysis

Customer occupations are analyzed to understand which professional groups contribute significantly to purchasing activity.

### Product Analysis

Product categories and individual products are analyzed to identify popular products and categories.

The project also identifies the top 10 products based on total orders using Pandas groupby and aggregation.

### Sales Analysis

The `Amount` column is used to analyze total sales across different customer segments and age groups.

Descriptive statistics show that the cleaned dataset has an average purchase amount of approximately **9,453.61**, with purchase amounts ranging from **188 to 23,952**.

## Key Insights

The analysis indicates that:

* Customers in the **26-35 age group** represent an important customer segment.
* Female customers within the 26-35 age group show strong purchasing activity.
* Customer purchasing behavior varies across states, occupations and product categories.
* Product-level analysis can be used to identify the most frequently ordered products.
* Customer demographics can help businesses identify important target segments.

The notebook's final analysis identifies married women aged 26-35 from Uttar Pradesh, Maharashtra and Karnataka, particularly those working in IT, Healthcare and Aviation, as a notable purchasing segment for Food, Clothing and Electronics.

## Project Workflow

```text
Raw Dataset
     ↓
Data Loading
     ↓
Data Inspection
     ↓
Data Cleaning
     ↓
Missing Value Handling
     ↓
Data Type Conversion
     ↓
Exploratory Data Analysis
     ↓
Visualization
     ↓
Customer & Product Insights
     ↓
Business Recommendations
```

## Project Structure



## Business Applications

The insights from this analysis can help businesses:

* Identify high-value customer segments
* Understand customer demographics
* Improve product targeting
* Identify high-performing product categories
* Focus marketing campaigns on relevant customer groups
* Develop more targeted Diwali sales strategies

## Future Improvements

Possible improvements to the project include:

* Building an interactive Power BI dashboard
* Adding advanced customer segmentation
* Performing RFM analysis
* Creating state-wise sales maps
* Developing sales KPIs
* Adding interactive filters and slicers
* Performing predictive sales analysis
* Creating automated reporting

## Conclusion

This project demonstrates how Python-based exploratory data analysis can transform raw retail transaction data into actionable business insights. By analyzing customer demographics, geography, occupations, products and sales amounts, businesses can better understand purchasing behavior and design more targeted marketing strategies.

## Author

**Ankit Mishra**

B.Tech – Artificial Intelligence & Data Science

---

### Tools & Technologies

`Python` `Pandas` `NumPy` `Matplotlib` `Seaborn` `Jupyter Notebook` `Data Analysis` `EDA` `Data Visualization`
