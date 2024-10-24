# Bank Stocks EDA

This repository contains a Jupyter Notebook for performing exploratory data analysis (EDA) on bank stock prices. The analysis focuses on the stock prices of major banks from the financial crisis of 2007-2008 to early 2016.

## Project Overview

The project aims to practice visualization and pandas skills by analyzing the stock prices of the following banks:
- Bank of America
- CitiGroup
- Goldman Sachs
- JPMorgan Chase
- Morgan Stanley
- Wells Fargo

## Data

The data is sourced from Kaggle and includes stock information for the aforementioned banks.

## Analysis

The notebook includes the following analyses:
1. **Data Import and Setup**: Importing necessary libraries and setting up the environment.
2. **Data Loading**: Loading stock data for the banks.
3. **Exploratory Data Analysis (EDA)**:
   - Maximum close price for each bank's stock.
   - Calculation of daily returns for each bank's stock.
   - Visualization of stock returns using pair plots.
   - Identification of best and worst single-day returns.
   - Standard deviation analysis to classify the riskiest stocks.
   - Distribution plots for stock returns.
4. **Visualization**:
   - Line plots showing the close price for each bank.
   - Heatmap and clustermap of the correlation between the stocks' close prices.
5. **Technical Analysis**:
   - Candle plot for Bank of America's stock.
   - Simple Moving Averages plot for Morgan Stanley.
   - Bollinger Band plot for Bank of America.

## Requirements

- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- seaborn
- matplotlib
- cufflinks
- plotly

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Disclaimer

This project is for educational purposes only and is not intended to provide financial advice.
