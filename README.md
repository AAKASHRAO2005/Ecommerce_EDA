
# E-commerce Exploratory Data Analysis & Data Cleaning

## Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) and Data Cleaning on an E-commerce dataset using Python.

The objective is to understand the dataset, identify and handle data quality issues, explore sales patterns, analyze product performance, and generate meaningful business insights through data visualization.

The project uses three datasets containing order information, order details, and sales targets.

## Objectives

- Understand the structure and characteristics of the datasets.
- Perform data quality assessment.
- Identify and handle missing values.
- Detect and remove duplicate records where appropriate.
- Handle inconsistent data formats and incorrect data types.
- Perform Exploratory Data Analysis (EDA).
- Analyze sales, profit, product categories, and order trends.
- Create meaningful visualizations.
- Generate actionable business insights.
- Export cleaned datasets for further analysis.

## Datasets

The project contains three datasets:

| Dataset | Description |
|---|---|
| List of Orders.csv | Contains order information and customer details. |
| Order Details.csv | Contains product-level information, including category, quantity, amount, and profit. |
| Sales target.csv | Contains monthly sales targets for different product categories. |

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Visual Studio Code

## Project Structure

```text
Ecommerce_EDA/
│
├── data/
│   ├── raw/
│   │   ├── List of Orders.csv
│   │   ├── Order Details.csv
│   │   └── Sales target.csv
│   │
│   └── processed/
│
├── notebooks/
│   └── Ecommerce_EDA.ipynb
│
├── visualizations/
│
├── reports/
│
├── requirements.txt
└── README.md
```

## Project Workflow

### 1. Data Loading
- Import required Python libraries.
- Load all three CSV datasets using Pandas.
- Display sample records and dataset dimensions.

### 2. Data Understanding
- Inspect column names and data types.
- Generate descriptive statistics.
- Understand numerical and categorical variables.

### 3. Data Cleaning
- Identify missing values.
- Detect duplicate records.
- Handle inconsistent formatting.
- Convert date columns into appropriate datetime formats.
- Validate numerical columns.
- Investigate potential outliers.

### 4. Data Integration
- Merge Orders and Order Details using the Order ID column.
- Maintain the Sales Target dataset for monthly target analysis.

### 5. Exploratory Data Analysis
- Perform univariate analysis.
- Perform bivariate analysis.
- Perform multivariate analysis.
- Explore sales and profit distributions.
- Analyze product category performance.
- Examine monthly sales trends.

### 6. Data Visualization

Create visualizations using Matplotlib and Seaborn, including:

- Category-wise sales analysis.
- Category-wise profit analysis.
- Monthly sales trends.
- Numerical distributions.
- Correlation heatmaps.
- Outlier detection using boxplots.

### 7. Business Insights

Identify important patterns and trends from the analysis to support business understanding and data-driven decision-making.

### 8. Data Export

Export cleaned datasets into the `data/processed/` directory for future analysis.

## Installation and Setup

### Prerequisites

- Python 3.10 or above
- Visual Studio Code
- Jupyter Notebook extension

### Step 1: Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd Ecommerce_EDA
```

### Step 2: Create a Virtual Environment

```bash
python -m venv venv
```

### Step 3: Activate the Environment

For Windows PowerShell:

```powershell
.\venv\Scripts\Activate.ps1
```

### Step 4: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 5: Launch Jupyter Notebook

```bash
jupyter notebook
```

Alternatively, open `notebooks/Ecommerce_EDA.ipynb` directly in VS Code.

## Requirements

```text
pandas
numpy
matplotlib
seaborn
jupyter
ipykernel
openpyxl
```

## Expected Outcomes

- Clean and structured E-commerce datasets.
- Improved data quality.
- Better understanding of sales and profit patterns.
- Identification of top-performing product categories.
- Insights into monthly sales performance.
- Meaningful visualizations.
- Analysis-ready datasets for future business intelligence tasks.

## Conclusion

This project demonstrates the practical application of Python-based data analytics techniques in an E-commerce business scenario.

By combining data cleaning, exploratory data analysis, data integration, and visualization, the project aims to transform raw data into meaningful business insights.

## Author

**Akash**

Data Analytics | Python | Pandas | SQL

---

*Developed as a practical Data Analytics project using Python and Jupyter Notebook.*