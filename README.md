# Machine Learning Essentials Part 1

## Overview
This repository documents my learning journey through the foundational concepts of data science and machine learning. Each section represents a key area of practice—from data cleaning and visualization to scraping and modeling. These Jupyter notebooks are structured to build understanding through hands-on implementation.

Below is a breakdown of each module by folder.

### 📁 `data`
Contains sample datasets used throughout the notebooks, including:
- `iris.csv` and `iris.data.csv`: The classic Iris flower dataset.
- `mtcars.csv`: Motor Trend Car Road Tests dataset.
- `Superstore-Sales.csv`: Retail sales data used for business analytics exercises.

### 📁 `Data Preparation`
Covers fundamental data cleaning and transformation techniques:
- **Concatenating and transforming.ipynb**: Combines multiple DataFrames and transforms columns.
- **Grouping and Aggregation(1).ipynb**: Groups data by index and aggregates values.
- **Grouping and Aggregation.ipynb**: Groups by column and applies summary statistics.
- **Removing Duplicates.ipynb**: Identifies and removes duplicate rows.
- **Treating Missing Values.ipynb**: Detects and handles missing values using pandas.

### 📁 `Data Sourcing through Web Scraping`
Demonstrates techniques for collecting data from the web:
- **AsynchronousWebScraper.ipynb**: Uses async requests to scrape multiple sites efficiently.
- **BeautifulSoup.ipynb**: Parses HTML documents and extracts content.
- **DataParsing.ipynb**: Extracts structured data from raw sources like HTML and JSON.
- **NavigableString.ipynb**: Navigates HTML nodes with BeautifulSoup.
- **Python Request for Automating Data.ipynb**: Automates web data extraction using the `requests` library.
- **WebScraping_GOV.ipynb**: Scrapes structured data from a government site.

### 📁 `Data Visualization`
Focuses on generating and customizing plots using Matplotlib and Seaborn:
- **Creating Labels and Annotations.ipynb**: Adds text and markers to plots.
- **Creating Standard Data Graphics.ipynb**: Builds line and bar plots.
- **Defining Elements of a Plot.ipynb**: Configures ticks, axes, and subplot layouts.
- **Matplot and Seaborn.ipynb**: Compares basic plots using both libraries.
- **Plot Formatting.ipynb**: Enhances chart aesthetics and layout.
- **Statistical Data Graphs in Seaborn.ipynb**: Visualizes distributions with Seaborn plots.
- **Visualizing Time Series.ipynb**: Plots time-based data and formats datetime axes.

### 📁 `Exploratory Data Analysis`
Performs preliminary data investigations and descriptive stats:
- **Extreme Value Analysis.ipynb**: Detects and visualizes outliers.
- **General Summary Stats.ipynb**: Generates core descriptive statistics.
- **MultiVar Analysis for Outliers.ipynb**: Identifies multivariate anomalies.
- **Pearson Correlation Stats.ipynb**: Measures linear relationships.
- **Simple Arithmetic.ipynb**: Demonstrates NumPy operations.
- **Spearman Rank Correlation and ChiSquare.ipynb**: Assesses monotonic relationships and categorical independence.
- **Summarizing Categorical Data.ipynb**: Counts and analyzes category data.

### 📁 `Fundamentals of Machine Learning`
Introduces core ML tasks and preprocessing techniques:
- **Applied Machine Learning.ipynb**: Prepares features and targets for ML models.
- **Cleaning and Treating Categorical Var.ipynb**: Encodes categorical features for modeling.
- **Transforming Data Set Distribution.ipynb**: Normalizes or scales features.
