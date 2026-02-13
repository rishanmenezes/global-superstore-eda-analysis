Global Superstore EDA Analysis

This project is based on Exploratory Data Analysis (EDA) performed on the Global Superstore 2016 dataset. The main aim of this project is to analyze the dataset and extract meaningful business insights related to sales, profit, discount, customer segments, shipping details, and product categories.
The dataset contains information about orders placed across different countries and regions, including details like order date, ship date, sales, profit, discount, product category, and customer information.
In this project, the dataset is first loaded and basic information such as shape, column names, and statistical summary is checked. Then the data is cleaned by removing unwanted spaces in column names and converting date columns into datetime format. After cleaning, additional useful columns such as year, month, and month name are created from the order date column to help in time-based analysis.

Two important calculated columns are also created:
Total Cost, calculated as Sales minus Profit
Discount Amount, calculated as Discount multiplied by Sales

After preprocessing, the project focuses on understanding total sales, total profit, and total cost. Different visualizations are created using Matplotlib to compare sales and profit trends and to study the impact of discounts.
The project provides insights that can help businesses identify profitable categories, understand sales patterns over time, and evaluate the effect of discounting strategies on profit.

Tools and Technologies Used:
Python programming language is used along with libraries such as Pandas, NumPy, Matplotlib, and OpenPyXL for reading the Excel dataset.

Files Included in the Project:
Global_superstore.ipynb (Notebook containing complete EDA code)
global_superstore_2016.xlsx (Dataset file)

How to Run the Project:
To run this project, download the notebook and dataset, install required libraries such as pandas, numpy, matplotlib, and openpyxl, then run the notebook in Jupyter Notebook or Google Colab.

Conclusion:
This project gives a complete exploratory analysis of the Global Superstore dataset and helps understand important trends in sales, profit, and discount impact. It can be useful for business decision making and improving sales and profitability strategies.

Author:
Rishan Menezes
