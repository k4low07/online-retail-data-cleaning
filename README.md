# Online Retail Data Cleaning with Python

## Project Overview

This project focuses on cleaning and preparing a real-world e-commerce dataset for further analysis using Python and Pandas.

The dataset contains over 500,000 transaction records from an online retail store. The main objective was to identify and handle missing values, duplicate records, incorrect data types, and data quality issues to create a reliable dataset for future business analysis.

---

## Dataset

Source: Online Retail Dataset

The dataset includes:

* Customer transactions
* Product information
* Order quantities
* Unit prices
* Invoice dates
* Customer IDs
* Country information

---

## Business Problem

Raw business data often contains errors and inconsistencies that can negatively impact analysis and decision-making.

The goal of this project was to:

* Detect missing values
* Remove duplicate records
* Identify invalid transactions
* Standardize data formats
* Prepare a clean dataset for future analytics

---

## Tools Used

* Python
* Pandas
* Jupyter Notebook

---

## Data Cleaning Process

The following steps were performed:

### 1. Data Inspection

* Loaded the dataset
* Reviewed data structure
* Checked data types
* Examined missing values

### 2. Missing Values Analysis

* Identified null values
* Evaluated their impact on analysis
* Applied appropriate cleaning methods

### 3. Duplicate Detection

* Searched for duplicated transactions
* Removed duplicate records where necessary

### 4. Data Quality Validation

* Checked for incorrect quantities
* Reviewed pricing anomalies
* Investigated unusual transactions

### 5. Final Dataset Preparation

* Cleaned and standardized the dataset
* Prepared data for future exploratory analysis

---

## Project Structure

online-retail-data-cleaning/

├── data/

├── notebooks/

│ └── analysis.ipynb

├── README.md

---

## Results

Original dataset:
- 541,909 records

After removing missing CustomerID:
- 406,829 records

Duplicates removed:
- 5,225 rows

Negative quantity transactions removed:
- 8,872 rows

Final cleaned dataset:
- 392,692 records

## Key Learnings

Through this project I practiced:

* Data cleaning techniques
* Data quality assessment
* Working with real-world datasets
* Pandas data manipulation
* Preparing datasets for analysis

---

## Future Improvements

Potential next steps:

* Exploratory Data Analysis (EDA)
* Customer segmentation
* Sales trend analysis
* Product performance analysis
* Data visualization using Matplotlib and Seaborn

---

## Author

Kacper Wolak

Junior Data Analyst in training

Python | SQL | Pandas | Excel
