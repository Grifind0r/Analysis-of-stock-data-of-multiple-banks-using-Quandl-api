# Analysis-of-stock-data-of-multiple-banks-using-Quandl-api
The analysis of the stock data for multiple banks, offering insights into their trading patterns, risk levels, and overall performance over the specified time period. The visualizations and computations conducted will aid in making informed investment decisions and understanding the dynamics of the banking sector in the stock market

## Tools Used
- Python
- NumPy
- Pandas
- Matplotlib
- Quandl API

## Steps
1. **Data Retrieval:**
   - Utilize the Quandl API to retrieve historical stock data for the specified companies (HBL, ABL, UBL, BOP) from January 1, 2011, to July 30, 2021.
   - Ensure that the data includes attributes such as date, open price, close price, volume, etc.

2. **Data Exploration:**
   - Examine the retrieved data to understand its structure and attributes.
   - Check for any missing values or inconsistencies in the data.

3. **Visualization:**
   - Visualize the total turnover of stock being traded each day for all companies using subplots.
   - Visualize the daily price change in stock using the formula (open price – previous close price).
   - Plot the monthly and yearly mean of close price for each bank.
   - Plot the Daily Returns using the formula (previous close/close)-1.
   - Identify and display the dates each bank stock had the best and worst single day returns.

4. **Risk Analysis:**
   - Calculate the standard deviation of daily returns for each bank stock to determine the level of risk.
   - Make a bar chart to visualize and compare the risk levels of each bank stock over the entire time period.

5. **Additional Visualizations:**
   - Make a line plot showing the Close price for each bank for the entire time in a single graph.
   - Create three more interesting visualizations based on the stock data to explore different aspects such as volume trends, correlation between stocks, or comparison of performance during significant market events.
   - Analyze and interpret the findings from these visualizations.

## Conclusion
The project aims to provide valuable insights into the stock data of multiple banks, facilitating better understanding and decision-making in the realm of investments. By leveraging various tools and techniques, it sheds light on the performance, risks, and trends associated with these bank stocks, contributing to informed decision-making in the financial domain.

## Code
The code for this project can be found in the **project.ipynb** notebook. It includes all the necessary steps for data retrieval, exploration, visualization, and analysis as outlined above.

**Note:** Ensure that the necessary libraries such as NumPy, Pandas, and Matplotlib are installed to execute the code successfully. Additionally, an API key from Quandl is required for data retrieval.
