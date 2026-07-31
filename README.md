# Python for Data Science

This repository contains my Python learning journey and hands-on practice in **Python Programming, Data Analysis, and Data Science**.

It includes Jupyter Notebooks covering Python fundamentals, functions, Pandas, data manipulation, and a COVID-19 data analysis project.

---

## 📂 Repository Contents

### 1. MasteringPythonZeroToHero.ipynb

This notebook covers Python programming fundamentals.

**Topics covered:**
- Variables and Data Types
- Operators
- Conditional Statements
- Loops
- Lists
- Tuples
- Sets
- Dictionaries
- Strings
- Functions
- Basic Python Programming

---

### 2. MasteringPythonZeroToHero_part2.ipynb

This notebook continues Python learning with concepts useful for Data Science and Data Analysis.

**Topics covered:**
- NumPy
- Pandas
- Series and DataFrames
- Reading datasets
- Data Cleaning
- Filtering and Sorting
- GroupBy Operations
- Data Aggregation
- Handling Missing Values
- Data Analysis

---

### 3. coronavirus-trend-analysis.ipynb

This is a COVID-19 Data Analysis project created using Python and Pandas.

**Analysis performed:**
- Dataset Exploration
- Data Cleaning
- Country-wise Analysis
- Date-wise Analysis
- Confirmed Cases Analysis
- Deaths Analysis
- Recovered Cases Analysis
- GroupBy and Aggregation
- COVID-19 Trend Analysis
- Data Visualization

---

### 4. my_universal_functions.py

This Python file contains reusable functions created while practicing Python programming.

---

## 🛠️ Technologies & Libraries

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn

---

## 📊 COVID-19 Data Analysis

The COVID-19 project demonstrates how Python and Pandas can be used to analyze real-world datasets.

Country-wise aggregation example:

```python
df.groupby('Country')[['Confirmed', 'Deaths', 'Recovered']].sum()
