# PyDataAnalysis

## Overview

A Python-based data analysis project that analyzes an Indian household dataset using Pandas, demonstrating data preprocessing, exploratory data analysis (EDA), feature engineering, data cleaning, filtering, grouping, aggregation, statistical analysis, and data visualization with Matplotlib.

The analysis is implemented in a Google Colab notebook and provides meaningful insights into household income, expenses, savings, education levels, and state-wise statistics.

---

## Features

### 1. Load CSV Dataset

Reads the Indian Household dataset using Pandas.

The notebook automatically loads:

```
data/indian_households.csv
```

and prepares it for analysis.

---

### 2. Dataset Inspection

Displays important information about the dataset including:

- First 5 Records
- Last 6 Records
- Dataset Shape
- Column Names
- Data Types
- Descriptive Statistics

This helps understand the structure and quality of the dataset before analysis.

---

### 3. Data Cleaning

Performs multiple cleaning operations including:

- Removing duplicate records
- Handling missing values
- Filling missing numerical values using the median
- Filling missing categorical values
- Verifying cleaned data

This ensures the dataset is ready for accurate analysis.

---

### 4. Feature Engineering

Creates a new column:

```
Savings = Monthly Income − Monthly Expense
```

This derived feature provides additional insights into household financial status.

---

### 5. Data Filtering

Allows filtering of households based on different conditions such as:

- High Income Households
- House Owners
- Large Families
- Graduate Families

This demonstrates practical data querying using Pandas.

---

### 6. Data Grouping & Aggregation

Groups data using various categories to generate insights such as:

- Average Monthly Income by State
- Average Monthly Expense by State
- Average Monthly Savings by State
- Average Income by Education Level
- Household Count by State

The project also calculates:

- Mean
- Maximum
- Minimum
- Total Records

using Pandas aggregation functions.

---

### 7. Data Visualization

Generates charts using Matplotlib.

Charts included:

- Average Monthly Income by State
- Education Level Distribution
- Average Monthly Savings by State

All charts are automatically saved inside:

```
output/
```

---

### 8. Export Cleaned Dataset

The cleaned dataset is exported as:

```
output/cleaned_households.csv
```

allowing further analysis or future use.

---

### 9. Summary Report

Generates a summary report containing:

- Total Households
- Average Income
- Average Expense
- Average Savings
- Highest Income
- Lowest Income
- Highest Savings
- Lowest Savings

The report is saved as:

```
output/summary.txt
```

---

## Folder Structure

```text
PyDataAnalysis/
├── Indian_Household_Data_Analysis.ipynb    # Main analysis notebook
├── README.md                              # Project documentation
├── requirements.txt                       # Required Python packages
├── .gitignore                             # Files excluded from Git
│
├── data/
│   └── indian_households.csv              # Dataset
│
├── output/
│   ├── cleaned_households.csv
│   ├── income_by_state.png
│   ├── education_distribution.png
│   ├── savings_by_state.png
│   └── summary.txt
│
└── screenshots/
    ├── Screenshot(1).jpeg
    ├── Screenshot(2).jpeg
    ├── Screenshot(3).jpeg
    ├── Screenshot(4).jpeg
    ├── Screenshot(5).jpeg
    ├── Screenshot(6).jpeg
    └── Screenshot(7).jpeg
```

> The `output/` folder is automatically generated after running the notebook. The `screenshots/` folder contains sample outputs and visualizations for the GitHub repository.

---

## Requirements

- Python 3.9 or later
- Google Colab (Recommended) or Jupyter Notebook

---

## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/kshethra-biyyala/PyDataAnalysis.git
```

---

### 2. Navigate to the project folder

```bash
cd PyDataAnalysis
```

---

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

---

### 4. Open the Notebook

Open the notebook in **Google Colab** (recommended) or **Jupyter Notebook**.

```
Indian_Household_Data_Analysis.ipynb
```

Run all cells from top to bottom.

> **Note:** If using Google Colab, upload `indian_households.csv` before executing the notebook.

---

## Dataset Information

**Dataset Name**

```
Indian Household Dataset
```

The dataset contains information about Indian households including:

- Household ID
- State
- City
- Family Size
- Monthly Income
- Monthly Expense
- House Ownership
- Education Level

The dataset also includes a few intentionally added missing values and duplicate records to demonstrate data cleaning techniques.

---

## Sample Analysis Performed

The notebook performs analysis such as:

- High Income Households
- Home Ownership Analysis
- Large Family Analysis
- Graduate Household Analysis
- State-wise Income Comparison
- State-wise Savings Comparison
- Education-wise Income Analysis

---

## Output Files

After execution, the notebook generates the following files inside the `output/` directory:

```
cleaned_households.csv
income_by_state.png
education_distribution.png
savings_by_state.png
summary.txt
```

Representative screenshots of the analysis and generated charts are also included in the `screenshots/` folder for quick preview on GitHub.

---

## Screenshots

### Dataset Preview

![Dataset Preview](screenshots/Screenshot(3).jpeg)

### Education Level Distribution

![Education Distribution](screenshots/Screenshot(6).jpeg)

### Average Monthly Savings by State

![Savings by State](screenshots/Screenshot(7).jpeg)

---

## Technologies Used

- Python 3
- Pandas
- NumPy
- Matplotlib
- Google Colab

---

## Skills Demonstrated

- Loading CSV datasets using Pandas
- Data inspection and exploratory data analysis (EDA)
- Data cleaning and preprocessing
- Handling missing values and duplicate records
- Feature engineering
- Data filtering and sorting
- Grouping and aggregation using Pandas
- Statistical analysis
- Data visualization using Matplotlib
- Exporting cleaned datasets and summary reports

---

## Author

**Biyyala Kshethra**

https://github.com/kshethra-biyyala