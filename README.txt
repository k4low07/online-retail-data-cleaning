# Online Retail Data Cleaning with Python

## Project Overview

This project focuses on cleaning and preparing a real-world e-commerce dataset for further analysis.

The dataset contains over 500,000 transaction records from an online retail store. The main goal was to identify and handle missing values, duplicates, incorrect records, and prepare the data for future business analysis.

---

## Dataset

Source: Online Retail Dataset

The dataset includes:

- Customer transactions
- Product information
- Order quantities
- Prices
- Purchase dates
- Customer IDs
- Countries

---

## Tools Used

- Python
- Pandas
- Jupyter Notebook

---

## Data Cleaning Process

### 1. Initial Data Exploration

- Checked dataset structure
- Reviewed data types
- Identified missing values
- Generated descriptive statistics

### 2. Handling Missing Values

- Removed records without CustomerID
- Verified remaining missing values

### 3. Removing Duplicates

- Identified duplicate rows
- Removed duplicated records

### 4. Data Type Conversion

- Converted InvoiceDate to datetime format
- Converted CustomerID to integer type

### 5. Data Quality Checks

- Removed transactions with negative quantities
- Removed records with zero prices

### 6. Feature Engineering

- Created a Revenue column:

```python
Revenue = Quantity * UnitPrice
```

---

## Results

Dataset size:

| Step | Rows |
|--------|--------:|
| Original dataset | 541,909 |
| After removing missing CustomerID | 406,829 |
| After removing duplicates | 401,604 |
| After removing negative quantities | 392,732 |
| Final cleaned dataset | 392,692 |

---

## Key Learnings

Through this project I practiced:

- Data cleaning with Pandas
- Handling missing values
- Removing duplicates
- Data validation
- Feature engineering
- Preparing datasets for analysis

---

## Future Improvements

- Customer segmentation
- Revenue analysis
- Top-selling products analysis
- Country-level sales analysis
- Data visualization dashboard

---

## Author

Kacper Wolak

Junior Data Analyst in Training