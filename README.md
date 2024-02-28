# Airbnb Business Performance Analysis in the NY,USA

## Project Overview

This project aims to analyze Airbnb business data across different cities in the USA to identify where the business is thriving. The insights from this analysis will guide the company's expansion strategy to focus on cities with the highest growth potential.

## Data Understanding

The dataset provided is in CSV format and contains records of Airbnb's business performance over the last few years across various cities. It includes a number of challenges that need to be addressed before conducting a thorough analysis:

- **Null Values**: The dataset contains numerous null entries that require careful treatment, either by removal or by imputing them with appropriate values such as mean or median, depending on the context and significance of the column.
- **Irrelevant Columns**: There are columns in the dataset that are not pertinent to our analysis and therefore will be dropped.
- **Outliers**: Outliers present in the dataset may skew our analysis and will be removed following standard statistical methods.

## Methodology

The analysis will follow these steps:

1. **Data Cleaning**: We'll begin by removing irrelevant columns and rows with null values that are not essential to our analysis. Outliers will be detected through IQR score or Z-score methods and removed to ensure they do not affect our results.

2. **Data Imputation**: For columns that are crucial to our analysis but contain null values, we will impute these missing entries with the mean or median of the column. The choice of mean or median will be based on the distribution of the data.

3. **Exploratory Data Analysis (EDA)**: We'll conduct an EDA to understand the trends, patterns, and anomalies in the data. This will include visualizations such as histograms, box plots, and scatter plots to understand the distribution and relationships between variables.

4. **Modeling**:used Decision Tree and Random Forest machine learning models to predict or classify price point points in different city. 

5. **Insight Generation**: Based on our analysis, we'll draw insights into where Airbnb's business is performing well and identify potential cities for expansion.

## Tools Used

- **Python**: For data manipulation and analysis, using libraries such as pandas, NumPy, and scikit-learn.
-** Matplotlib:used as a data visualization tool.
- **Jupyter Notebook**: For documenting the analysis process and findings.


## Conclusions

Added on the EDA Presentation File

## How to Use This Repository

- **Data Folder**: Contains the raw CSV file and the cleaned dataset.
- **EDA with coding & prediction model**: Contains Jupyter notebooks with all the analysis and code & Contains Python scripts for data cleaning and analysis.

## Contributing

We welcome contributions to this project! Please fork the repository and submit a pull request with your proposed changes.
