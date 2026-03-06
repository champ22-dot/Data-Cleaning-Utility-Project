# Data Cleaning Utility (Python, Pandas, NumPy)

## Overview
This project implements an automated **Data Cleaning Utility** that preprocesses raw datasets by detecting missing values, fixing incorrect data types, removing duplicates, and standardizing column names.

The goal is to transform messy raw data into a clean dataset suitable for analysis and machine learning.

---

## Features

- Detect and handle missing values
- Fix incorrect data types
- Parse date columns
- Remove duplicate records
- Standardize column names
- Generate cleaning logs
- Export cleaned dataset

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib

---

## Project Structure

data-cleaning-utility/
data/
raw/
Sample-Superstore.csv

cleaned/
cleaned_superstore.csv

logs/
cleaning_log.txt

diagrams/
pipeline_diagram.png
missing_value_strategy.png
workflow_diagram.png

src/
data_cleaning.py


---

## Data Cleaning Pipeline

![Pipeline](diagrams/pipeline_diagram.png)

---

## Missing Value Strategy

![Missing Values](diagrams/missing_value_strategy.png)

---

## Cleaning Workflow

![Workflow](diagrams/workflow_diagram.png)

---

## Installation

Install dependencies:


pip install pandas numpy matplotlib


---

## Usage

Run the cleaning script:


python src/data_cleaning.py


This will:

- Load the raw dataset
- Clean the data
- Export cleaned dataset
- Generate a cleaning log

---

## Example Cleaning Log


Standardized column names
Removed duplicate rows
Parsed date columns
Handled missing values using median/mode


---

## Future Improvements

- Automated data quality report
- Outlier detection
- Streamlit dashboard
- CLI-based dataset cleaning


