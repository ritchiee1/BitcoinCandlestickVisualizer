# Bitcoin Candlestick Chart Project

## Introduction
This project aims to create a candlestick chart for Bitcoin prices over the last 30 days. The chart is generated using data from the PyCoinGecko API, processed with pandas, and visualized with Plotly. The candlestick chart is saved as an HTML file for easy viewing.

## Problem Statement
Understanding Bitcoin price trends over a recent period is crucial for making informed investment decisions. This project provides a visual representation of Bitcoin's price fluctuations, helping users analyze market trends and price movements effectively.

## Skills Demonstrated
* Python Programming: Writing scripts to fetch, process, and visualize data.
* API Integration: Using PyCoinGecko API to retrieve cryptocurrency data.
* Data Processing: Utilizing pandas for data transformation and aggregation.
* Data Visualization: Creating interactive candlestick charts with Plotly.

## Data Sourcing
The data for this project is sourced from the CoinGecko API. Specifically, the get_coin_market_chart_by_id endpoint is used to fetch Bitcoin price data over the last 30 days.

## Data Transformation
The raw data from the API is in JSON format with UNIX timestamps. The transformation steps include:

* Conversion: UNIX timestamps are converted to readable date formats using pandas.
* Aggregation: Data is aggregated by day to prepare it for candlestick charting, with columns for minimum, maximum, opening, and closing prices.
##Modelling

No advanced statistical or machine learning models are applied in this project. The focus is on data aggregation and visualization.

## Analysis & Visualizations

* Candlestick Chart: A candlestick chart is generated to display Bitcoin price trends, including opening, closing, high, and low prices for each day.
* ![image](https://github.com/user-attachments/assets/143cf44d-6a31-4e6f-a02d-1fee6cfc507c)

* Interactive Visualization: The chart is saved as an HTML file for interactive exploration.
## Conclusion and Recommendation
This project provides a clear visual representation of Bitcoin’s price movements over the past 30 days. The candlestick chart is useful for identifying trends and making informed decisions about Bitcoin investments. Users are encouraged to explore the chart interactively to gain insights into market trends.
