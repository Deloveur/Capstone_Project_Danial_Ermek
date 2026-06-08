# Capstone Project Danial & Ermek

## Nike Retail Data Cleaning and Preparation

### Authors
- Danial
- Ermek

---

## Project Overview

This project focuses on cleaning, validating, and preparing Nike retail product data for business intelligence analysis and Power BI dashboard development.

The objective was to transform raw retail data into a clean and structured dataset suitable for reporting, visualization, and decision-making.

---

## Technologies Used

- Python
- Pandas
- Jupyter Notebook
- CSV Files
- Power BI
- GitHub

---

## Dataset Description

The project uses Nike retail product data containing information about:

- Product names
- Product categories
- Subcategories
- Country codes
- Prices
- Sale prices
- Gender segments
- Product identifiers
- Snapshot dates

Original dataset size:

- Rows: 103,679
- Columns: 35

---

## Data Cleaning Process

### Step 1. Dataset Loading

Loaded the Nike retail dataset using Pandas and verified successful import.

### Step 2. Dataset Overview

Reviewed dataset structure and inspected sample records.

### Step 3. Missing Values Analysis

Checked all columns for missing values.

Result:

- No missing values detected.

### Step 4. Duplicate Records Detection

Verified the dataset for duplicated rows.

Result:

- Duplicate rows found: 0

### Step 5. Data Type Transformation

Converted the `snapshot_date` column into datetime format for future analysis.

### Step 6. Removing Unnecessary Columns

Removed technical columns not required for business analysis:

- product_url
- canonical_url
- image_url

### Step 7. Exporting Clean Dataset

Saved the cleaned dataset as a CSV file for Power BI dashboard creation.

---

## Results

### Before Cleaning

- Rows: 103,679
- Columns: 35

### After Cleaning

- Rows: 103,679
- Columns: 32

### Data Quality Summary

- Missing values: 0
- Duplicate rows: 0
- Date format standardized
- Unnecessary columns removed

---

## Repository Structure

```text
Capstone_Project_Danial_Ermek
│
├── README.md
├── kapstown.ipynb
└── nike_cleaned.rar
```

### Archive Contents

```text
nike_cleaned.rar
│
├── NIKE_GLOBAL_CATALOGUE.csv
└── nike_cleaned.csv
```

---

## Business Value

The cleaned dataset can be used for:

- Sales analysis
- Product performance analysis
- Country-level comparisons
- Category analysis
- Power BI dashboard development
- Business intelligence reporting

---

## Conclusion

The Nike retail dataset was successfully cleaned, validated, and prepared for analytical use.

The final dataset contains structured and reliable information that can be used for visualization, reporting, and business decision-making in Power BI.
