SWYNEX Task 1: Data Cleaning & Preparation

Project Overview
This project focuses on cleaning and preparing the Customer Personality Analysis dataset using Python and Pandas.

Tools Used
- Python
- Pandas
- NumPy
- Google Colab

Dataset
The original dataset contains customer demographics, income, purchasing behavior, and marketing campaign information.

- Original dataset: 2,240 rows and 29 columns.
- Source: [Customer Personality Analysis — Kaggle](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis)

Data Cleaning Steps
1. Inspected dataset structure, column names, and data types.
2. Identified 24 missing values in the Income column.
3. Replaced missing Income values with the median income.
4. Checked for duplicate records; none were found.
5. Converted Dt_Customer to datetime format.
6. Standardized Absurd and YOLO marital-status values to Unknown.
7. Validated the cleaned dataset and exported it to CSV.

Final Results
- Rows retained: 2,240
- Columns retained: 29
- Missing values: 0
- Duplicate rows: 0
- Invalid dates: 0

Project Files
- `SWYNEX_Data_Cleaning.ipynb` — Python notebook containing the cleaning workflow.
- `marketing_campaign_cleaned.csv` — cleaned dataset.

Conclusion
The dataset was cleaned and validated for further analysis. Missing income values were imputed using the median, date formats were standardized, and nonstandard marital-status categories were handled consistently.