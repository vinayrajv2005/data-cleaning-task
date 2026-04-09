# Data Cleaning and Preprocessing Task

## Objective

To clean and prepare a raw dataset by handling missing values, duplicates, and inconsistent formats.

## Dataset

Customer Personality Analysis (Kaggle)

## Steps Performed

* Checked and handled missing values using `dropna()`
* Removed duplicate records using `drop_duplicates()`
* Standardized column names (lowercase, no spaces)
* Converted date column (`Dt_Customer`) to datetime format
* Fixed data types (e.g., `Year_Birth` to integer)

## Tools Used

* Python (Pandas)
* Google Colab

## Output

Cleaned dataset (`cleaned_data.csv`) ready for analysis.

## Repository Contents

- raw_data.csv
- cleaned_data.csv
- data_cleaning_task.ipynb
