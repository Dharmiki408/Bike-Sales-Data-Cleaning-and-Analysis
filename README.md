# task-1
# Bike Sales Data Cleaning and Analysis

This project involves cleaning and preprocessing a raw bike sales dataset using Python and Pandas. The dataset was obtained from Kaggle and includes customer demographics, sales figures, and product information.

##Files Included

- `cleaning_script.py` — Python script used to clean the dataset.
- `cleaned_bike_sales.xlsx` — Cleaned version of the original dataset.
- (Optional) `bike_sales_analysis.ipynb` — Jupyter Notebook with cleaning + EDA.

##Data Cleaning Steps

1. Handled Missing Values:
   - Filled missing values in `Day`, `Age_Group`, and `Product_Description`.
   - Used mode for categorical and median for numerical columns.

2. Removed Duplicates:
   - Removed duplicate rows to ensure data quality.

3. Standardized Text:
   - Trimmed whitespace and formatted text in categorical columns (e.g., `Customer_Gender`, `Country`).

4. Renamed Columns:
   - Converted all column names to lowercase and snake_case for consistency.

5. Fixed Data Types:
   - Converted `Date` column to datetime.
   - Ensured numerical columns (`unit_cost`, `unit_price`, `revenue`, etc.) have correct data types.

6. Converted Age and Day Columns:
   - Filled missing values and converted to `int` type.


## Tools Used

- Python 3.x
- Pandas
- Jupyter Notebook (optional)
- Excel for raw data
- GitHub for version control

##  Dataset Source

[📥 Bike Sales in Europe on Kaggle](https://www.kaggle.com/datasets/sadiqshah/bike-sales-in-europe)


## Author
k.dharmike 
[]

