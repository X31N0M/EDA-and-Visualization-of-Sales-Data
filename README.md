# Supermarket Sales EDA and Visualization

This repository contains exploratory data analysis (EDA) and visualization code for analyzing supermarket sales data. The dataset used is "supermarket_sales - Sheet1.csv". The analysis covers various aspects of the data, including descriptive statistics, data cleaning, feature engineering, outlier detection, and visualization.

## Getting Started

To get started, clone this repository to your local machine:

```bash
git clone https://github.com/X31N0M/EDA-and-Visualization-of-Sales-Data.git
```

Ensure you have Python and necessary libraries installed to run the code.

## Dataset

The dataset contains information about supermarket sales, including attributes such as:

- Branch: The supermarket branch (A, B, or C).
- Date: Date of the transaction.
- Customer type: Type of customer (Member or Normal).
- Product line: Category of the product.
- Unit price: Price of a single unit of the product.
- Quantity: Number of units purchased.
- Gross income: Total gross income from the transaction.
- Tax 5%: Tax amount (5% of total).
- Total: Total transaction amount.
- Payment: Payment method.
- COGS: Cost of goods sold.

## Analysis Overview

1. **Data Loading and Initial Exploration:**
   - Loading the dataset using Pandas.
   - Displaying the first and last few rows of the dataset.
   - Checking the shape, info, and descriptive statistics of the dataset.

2. **Data Cleaning and Preprocessing:**
   - Handling missing values.
   - Converting data types (e.g., date column to datetime).
   - Creating new columns for month and year.
   - Encoding categorical variables.

3. **Feature Engineering:**
   - Calculating percentage change in gross income.
   - Adding new features like month and year from the date column.
   - Scaling numerical features using MinMaxScaler.

4. **Exploratory Data Analysis (EDA):**
   - Visualizing data distributions using histograms and density plots.
   - Exploring the relationship between variables using scatter plots, pair plots, and correlation analysis.
   - Creating frequency tables and cross-tabulations.
   - Analyzing sales trends over time.

5. **Outlier Detection:**
   - Detecting outliers using statistical methods (Z-score, IQR).
   - Using Isolation Forest and Local Outlier Factor algorithms for outlier detection.
   - Handling outliers through techniques like log transformation, clipping, and mapping.

6. **Visualization:**
   - Visualizing sales trends, distributions, and relationships using line plots, bar charts, pie charts, histograms, box plots, and scatter plots.
   - Utilizing libraries like Matplotlib and Seaborn for visualization.
