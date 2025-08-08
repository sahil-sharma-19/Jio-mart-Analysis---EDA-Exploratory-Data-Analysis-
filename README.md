

# Jiomart Analysis - Data Analysis Project in Python

## Project Overview
This project performs exploratory data analysis (EDA) on a retail sales dataset from Jiomart, a leading online grocery platform in India. The primary objective is to analyze product-level and outlet-level data to uncover sales patterns, customer preferences, and store performance, which can inform business strategy and operational improvements.

## Dataset Description
- The dataset `jiomart_data.csv` contains 8,523 records of individual grocery product sales.
- Key features include:
  - **Product Attributes:** Fat Content, Identifier, Type, Weight, Item Visibility.
  - **Outlet Attributes:** Identifier, Location Type (Tier 1, 2, 3), Size, Type, Establishment Year.
  - **Sales and Ratings:** Sales values and customer ratings for products.

## Libraries Used
- `pandas` for data manipulation and cleaning.
- `numpy` for numerical computations.
- `matplotlib` and `seaborn` for data visualization.

## Analysis Steps

### 1. Importing Libraries
Python libraries needed for data analysis and visualization are imported.

### 2. Loading Dataset
The CSV dataset is loaded into a pandas DataFrame.

### 3. Data Preview
A snapshot of the dataset is displayed to understand the variables and sample values.

### 4. Data Cleaning
- Handle missing values, especially in columns like `Item Weight` and `Sales`.
- Standardize categorical columns such as `Item Fat Content` by correcting inconsistencies (e.g., ‘low fat’, ‘Low Fat’, ‘reg’, ‘Regular’).

### 5. Exploratory Data Analysis (EDA)
- Summary statistics of numeric features (Sales, Ratings, Item Weight).
- Frequency distribution of categorical attributes (Item Type, Outlet Size, Outlet Type).
- Identification of outliers and anomalies.
- Visualization of sales trends across different outlet types and locations.
- Correlation analysis between item visibility, sales, and ratings.

### 6. Insights and Recommendations
- Identification of best-performing product categories and outlets.
- Understanding impact of outlet location and type on sales.
- Recommendations for marketing focus and inventory management.

## How to Run This Notebook
- Ensure the data file `jiomart_data.csv` is placed in the correct directory or update the file path in the notebook.
- Run all notebook cells sequentially to reproduce the analysis.
- Modify or extend the notebook to include further analyses or predictive modeling if desired.

## Contact
For questions or contributions, please open an issue or submit a pull request.

---

*Thank you for exploring the Jiomart sales data analysis!*

