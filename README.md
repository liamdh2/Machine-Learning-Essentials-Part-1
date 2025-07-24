# Machine Learning Essentials Part 1

## Overview

This repository is part of my learning journey to build a strong foundation in machine learning and data science. It contains a variety of Python notebooks and datasets that cover core tasks like data handling, exploration, visualization, and basic machine learning techniques. Each section of the repository focuses on hands-on practice and conceptual understanding, reflecting an educational and exploratory approach to learning these fundamentals.

## Folder Breakdown

- **data/**: Sample datasets (CSV files) used in the notebooks (for example, the Iris and mtcars datasets and a Superstore Sales dataset). These provide real data for practicing loading and inspecting data in Python.  
- **Data Preparation/**: Notebooks that demonstrate techniques for cleaning and preparing data using pandas. This includes combining tables, handling missing values, removing duplicates, and other data manipulation tasks.  
- **Data Sourcing through Web Scraping/**: Notebooks illustrating how to collect data from the web. They cover methods like asynchronous requests, using BeautifulSoup to parse HTML, and using Python requests to automate data retrieval (including an example scraping a government website).  
- **Data Visualization/**: Notebooks focused on creating and customizing plots with Matplotlib and Seaborn. Topics include making standard charts, adding labels and annotations, formatting plot elements, and visualizing special data types like time series.  
- **Exploratory Data Analysis/**: Notebooks that perform basic data analysis to understand datasets. They include generating summary statistics, identifying extreme values or outliers, exploring correlations (Pearson and Spearman), and summarizing categorical data.  
- **Fundamentals of Machine Learning/**: Notebooks introducing the basics of applied machine learning. They cover setting up features and labels for a learning task, cleaning and encoding categorical variables, and transforming data distributions (such as normalization) in preparation for modeling.  

## File Descriptions

- `Data Preparation/Concatenating and transforming.ipynb`: Demonstrates how to concatenate multiple datasets and transform data using pandas, including adding or dropping columns in a DataFrame.  
- `Data Preparation/Grouping and Aggregation(1).ipynb`: Shows grouping data by index and performing aggregation operations (like computing summary statistics) using pandas.  
- `Data Preparation/Grouping and Aggregation.ipynb`: Illustrates how to group data by a column and apply aggregation functions (such as sum or average) using pandas `groupby`.  
- `Data Preparation/Removing Duplicates.ipynb`: Demonstrates how to identify duplicate rows in a DataFrame and remove them using pandas.  
- `Data Preparation/Treating Missing Values.ipynb`: Covers techniques for handling missing data, including detecting null entries and filling or dropping missing values in a DataFrame.  
- `Data Sourcing through Web Scraping/AsynchronousWebScraper.ipynb`: Illustrates how to use asynchronous programming (e.g., with `asyncio`) to perform web scraping concurrently and speed up data collection from multiple URLs.  
- `Data Sourcing through Web Scraping/BeautifulSoup.ipynb`: Introduces the BeautifulSoup library for scraping HTML, showing how to parse web pages and extract specific data elements or text.  
- `Data Sourcing through Web Scraping/DataParsing.ipynb`: Covers general parsing techniques for extracting information from raw data sources like HTML or JSON.  
- `Data Sourcing through Web Scraping/NavigableString.ipynb`: Shows how to work with BeautifulSoup’s NavigableString objects to navigate an HTML tree and retrieve text content.  
- `Data Sourcing through Web Scraping/Python Request for Automating Data.ipynb`: Demonstrates using the `requests` library in Python to fetch web pages and automate the collection of data from online sources.  
- `Data Sourcing through Web Scraping/WebScraping_GOV.ipynb`: Example of scraping data from a government or similarly structured website, illustrating the process of loading a page and saving results.  
- `Data Visualization/Creating Labels and Annotations.ipynb`: Shows how to add and customize labels, titles, and annotations on plots (using Matplotlib) to make the charts more informative.  
- `Data Visualization/Creating Standard Data Graphics.ipynb`: Demonstrates plotting basic chart types (such as line charts) using Matplotlib with example data.  
- `Data Visualization/Defining Elements of a Plot.ipynb`: Covers customizing plot elements like axes, ticks, and gridlines, and how to create multiple subplots within a single figure.  
- `Data Visualization/Matplot and Seaborn.ipynb`: Introduces plotting with both Matplotlib and Seaborn, showing examples of creating bar charts and other plots to compare the two libraries.  
- `Data Visualization/Plot Formatting.ipynb`: Focuses on styling plots (changing colors and line styles) and adjusting aesthetic elements to improve visual design.  
- `Data Visualization/Statistical Data Graphs in Seaborn.ipynb`: Demonstrates statistical plots in Seaborn such as histograms and scatter plots to visualize distributions and relationships in data.  
- `Data Visualization/Visualizing Time Series.ipynb`: Covers techniques for plotting time series data (e.g. dates on the x-axis) and customizing those plots for better readability.  
- `Exploratory Data Analysis/Extreme Value Analysis.ipynb`: Demonstrates identifying outliers and extreme values in a dataset using univariate methods like boxplots (Tukey's method).  
- `Exploratory Data Analysis/General Summary Stats.ipynb`: Shows how to generate basic summary statistics (mean, median, etc.) for numeric data using pandas and scipy.  
- `Exploratory Data Analysis/MultiVar Analysis for Outliers.ipynb`: Explores multivariate outlier detection, using methods like visual inspection of multiple boxplots or scatter plots.  
- `Exploratory Data Analysis/Pearson Correlation Stats.ipynb`: Introduces the Pearson correlation coefficient to measure linear relationships between two numeric variables.  
- `Exploratory Data Analysis/Simple Arithmetic.ipynb`: Demonstrates using NumPy arrays to perform basic arithmetic operations on data (addition, multiplication, etc.).  
- `Exploratory Data Analysis/Spearman Rank Correlation and ChiSquare.ipynb`: Covers non-parametric methods: the Spearman rank correlation for monotonic relationships and the Chi-square test for categorical data analysis.  
- `Exploratory Data Analysis/Summarizing Categorical Data.ipynb`: Shows how to summarize categorical variables (e.g. counting category frequencies) using pandas.  
- `Fundamentals of Machine Learning/Applied Machine Learning.ipynb`: Introduces a simple machine learning workflow: separating features and labels from a dataset and applying a basic model or algorithm.  
- `Fundamentals of Machine Learning/Cleaning and Treating Categorical Var.ipynb`: Demonstrates encoding categorical variables (using label encoding or one-hot encoding) so they can be used in machine learning models.  
- `Fundamentals of Machine Learning/Transforming Data Set Distribution.ipynb`: Explores transforming data distributions (like normalizing or scaling features) to prepare data for machine learning algorithms.  
