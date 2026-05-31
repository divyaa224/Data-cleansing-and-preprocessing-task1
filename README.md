# Mall Customer Data Cleaning Project

## Overview

This project focuses on cleaning and preparing the Mall Customer Segmentation dataset for further analysis. Data cleaning is a crucial step in any data analytics workflow, as the quality of insights depends heavily on the quality of the data.

Using Python and Pandas, I performed a series of data quality checks and preprocessing steps to ensure the dataset is consistent, accurate, and analysis-ready.

---

## Dataset Information

**Dataset:** Mall Customer Segmentation Dataset

The dataset contains customer information such as:

* Customer ID
* Gender
* Age
* Annual Income (k$)
* Spending Score (1–100)

---

## Tools & Technologies

* Python
* Pandas
* Google Colab
* GitHub

---

## Data Cleaning Process

### 1. Data Inspection

* Loaded the dataset using Pandas.
* Explored the dataset structure and column information.

### 2. Missing Value Analysis

* Checked for missing values using `.isnull().sum()`.
* Verified that the dataset contains no null values.

### 3. Duplicate Record Check

* Identified duplicate rows using `.duplicated()`.
* Confirmed that no duplicate records were present.

### 4. Column Standardization

* Renamed column headers to a consistent format:

  * Lowercase letters
  * Underscores instead of spaces

### 5. Text Standardization

* Standardized gender values by converting them to lowercase.
* Removed any unnecessary whitespace.

### 6. Data Type Validation

* Verified that numerical columns have appropriate data types.
* Ensured the dataset is ready for future analysis and visualization.

---

## Project Results

| Metric                  | Result                 |
| ----------------------- | ---------------------- |
| Total Records           | 200                    |
| Missing Values Found    | 0                      |
| Duplicate Records Found | 0                      |
| Columns Standardized    | 5                      |
| Dataset Status          | Clean & Analysis Ready |

---

## Files Included

* `Mall_Customers.csv` – Original dataset
* `Mall_Customers_Cleaned.csv` – Cleaned dataset
* `data_cleaning.ipynb` – Google Colab notebook containing the cleaning process

---

## Key Learnings

Through this project, I gained hands-on experience in:

* Data preprocessing
* Data quality assessment
* Handling missing values and duplicates
* Data standardization
* Using Pandas for real-world data cleaning tasks
* Maintaining reproducible workflows using Google Colab and GitHub

---

## Future Scope

The cleaned dataset can be used for:

* Customer Segmentation
* Exploratory Data Analysis (EDA)
* Data Visualization
* Machine Learning Models
* Marketing Strategy Analysis

---

## Author

**Divya Chaudhary**

B.Tech Computer Science Engineering

Aspiring Data Analyst | Data Science Enthusiast | AI & ML Learner
