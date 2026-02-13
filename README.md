PROJECT TITLE
- Global Superstore Data Analysis

PROJECT OVERVIEW
- This project is an Exploratory Data Analysis (EDA) of the Global Superstore dataset, a major retail dataset containing over 50,000 transaction records. The goal of this analysis is to understand sales trends, profitability, and operational costs across different international markets. By processing this data, we identify key growth areas, seasonal patterns, and high-performing customer segments to support business decision-making.

DATASET DESCRIPTION

The dataset ("Global Superstore 2016") contains three main tables:
1. Orders: The primary dataset with 51,290 rows containing transaction details like Order Date, Sales, Profit, Discount, and Customer Information.
2. Returns: A record of orders that were returned, linked by Order ID and Region.
3. People: A list of regional managers responsible for different markets.

OBJECTIVES OF THE PROJECT
- To analyze total sales and profit trends over the years (2012-2015).
- To identify the most profitable countries and those with the highest operational costs.
- To compare market performance, specifically looking at key regions like China, India, and Australia.
- To determine which customer segments drive the most volume.
- To detect seasonal patterns in sales data.

STEPS PERFORMED
1. Data Loading: Loaded the Excel/CSV files using Pandas and inspected the dataframe structure.
2. Data Cleaning:
   - Standardized column names (removed spaces and special characters).
   - Converted "Order Date" and "Ship Date" to datetime objects.
   - Checked for and handled missing values (specifically in Postal Code).
3. Feature Engineering:
   - Extracted Year and Month from dates for time-series analysis.
   - Created a "Total Cost" column (Sales - Profit) to analyze spending.
   - Calculated "Discount Amount" to see how much revenue was given up in promotions.
4. Data Visualization: Used Matplotlib to create bar charts, line graphs, and pie charts to visualize trends.
5. Insight Generation: derived specific business metrics like year-over-year growth and regional comparisons.

TOOLS AND LIBRARIES USED
- Python
- Pandas (for data manipulation)
- NumPy (for numerical calculations)
- Matplotlib (for data visualization)
- Jupyter Notebook

FILES INCLUDED
- Global_superstore.ipynb: The main analysis notebook containing all code and charts.
- global_superstore_2016.xlsx - Orders.csv: Raw sales data.
- global_superstore_2016.xlsx - Returns.csv: Returns data.
- global_superstore_2016.xlsx - People.csv: Regional manager data.

HOW TO RUN THE PROJECT
1. Install the required Python libraries:
   pip install pandas numpy matplotlib openpyxl
2. Download all the CSV files and the Jupyter Notebook into the same folder.
3. Open "Global_superstore.ipynb" in Jupyter Notebook or VS Code.
4. Run the cells in order to see the analysis and graphs.

KEY INSIGHTS
- Sales Growth: There was a significant increase in sales in 2015 compared to 2014, with a difference of approximately $432,485.
- Top Markets: India proved to be a highly profitable market with a total profit of over $129,000.
- Customer Segments: The "Consumer" segment is the largest, accounting for over 26,500 orders (more than half of the total dataset).
- Seasonality: Sales show a clear upward trend towards the end of the year, likely due to holiday seasons.
- Operational Costs: We identified specific countries where the "Total Cost" of operations is disproportionately high compared to sales.

CONCLUSION
-The analysis confirms that the Global Superstore is growing year-over-year, with the Consumer segment being the primary revenue driver. However, operational costs in certain regions and the impact of discounts on profit margins require careful management. This project demonstrates the ability to handle large datasets and derive meaningful business intelligence using Python.

AUTHOR
-Rishan Menezes
