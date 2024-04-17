# MercadoLibre Search Trends and Stock Price Analysis

## Overview

This project analyzes MercadoLibre's Google search trends and correlates these trends with stock price movements. The goal is to determine if there's a predictive relationship between search traffic and stock performance, and to forecast future trends using the Prophet time-series model.

## Installation

The code requires Python 3 and the following libraries:
- pandas
- prophet
- matplotlib
- seaborn
- numpy

To install the necessary libraries, run the following command:
```
!pip install pandas matplotlib seaborn numpy prophet
```

## Usage

The script is divided into several major sections, each corresponding to a specific analysis or modeling step:

1. **Data Loading and Preliminary Analysis**
   - Load Google search traffic data and stock price data.
   - Visualize data and identify unusual patterns or seasonal trends.

2. **Data Preprocessing**
   - Prepare data for analysis by setting appropriate indices and renaming columns.

3. **Data Concatenation**
   - Merge search traffic data with stock price data to analyze correlations.

4. **Time Series Forecasting with Prophet**
   - Fit a Prophet model to search traffic data to predict future trends.
   - Decompose time series data to analyze underlying patterns.

Each step includes visualizations to aid in understanding the data's characteristics and the model's predictions.

## Detailed Steps

### Step 1: Unusual Pattern Detection in Search Traffic

- **Objective**: Identify unusual search traffic patterns and link them to financial events.
- **Methods Used**: Time series slicing and visualization.

### Step 2: Seasonality Mining

- **Objective**: Explore seasonal patterns in hourly, daily, and weekly search traffic.
- **Methods Used**: Groupby operations and visualizations such as line plots and heatmaps.

### Step 3: Correlation Analysis

- **Objective**: Investigate the relationship between search traffic and stock prices.
- **Methods Used**: Data concatenation, correlation matrix calculation, and lagged variable creation.

### Step 4: Time Series Forecasting

- **Objective**: Forecast future search trends using Prophet.
- **Methods Used**: Prophet modeling, future data frame creation, and result plotting.

## Results

- The analysis provides insights into the correlation between search traffic and stock prices.
- Seasonal trends and unusual patterns are identified and linked to specific time frames.
- The Prophet model forecasts future search trends, providing valuable information for strategic decision-making.

## Visualization

- **Stock Volatility**: Plotted over time to analyze risk and uncertainty.
- **Search Trends**: Forecasted trends visualized to anticipate future changes in search behavior.
- **Seasonality Components**: Visualized to understand the daily and weekly patterns.

## Conclusion

The project highlights the potential of using search traffic data to predict stock performance, although further research and more complex models might be needed to improve prediction accuracy.

## Contribution

Feel free to fork this repository, make changes, and submit pull requests. Contributions to expand on the analysis or improve the modeling are welcome.

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

- Creator - [Ken Stager](mailto:kenstager@hotmail.com)
- Project Link: [Prophet Challenge](https://github.com/KenStager/prophet-challenge/tree/main)
