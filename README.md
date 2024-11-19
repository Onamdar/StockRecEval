# Stock Recommendation Algorithm Evaluation

This repository contains the evaluation and analysis tools for a stock recommendation algorithm that has been operational since February 2019. While the core algorithm is not included, this repository provides the dataset and evaluation notebook used to analyze the algorithm’s performance and trading signals.

## Files Included

1. **`signals.csv`**: A dataset containing historical trading signals, including:
   - Buy and sell dates
   - Stock symbols
   - Buy and sell prices
   - Profits
   - Trade status (successful/unsuccessful)

2. **`eval.ipynb`**: A Jupyter Notebook used for:
   - Evaluating the algorithm's performance
   - Generating profit distribution visualizations
   - Identifying top-performing stocks and trades
   - Highlighting areas for improvement through statistical analysis

## Key Features

- **Profit Analysis**: Analyze the overall profitability and performance of trading signals.
- **Top Performers**: Identify the most profitable stocks and trades based on historical data.
- **Loss Evaluation**: Examine trades with significant losses to understand areas for improvement.
- **Visualization**: Includes graphs and charts for profit distributions, individual stock performance, and trading activity.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/Onamdar/StockRecEval.git

2. Open the `eval.ipynb` notebook in Jupyter or any compatible IDE:

   ```bash
   jupyter notebook eval.ipynb

## Follow the Notebook Cells to:

- **Perform data exploration**
- **Conduct profitability analysis**
- **Visualize trade signals and performance**

## Dataset Overview

- **Timeframe**: February 2019 to October 2024
- **Total Trades**: 723
- **Successful Trades**: 505
- **Unsuccessful Trades**: 218

## Next Steps

This repository serves as an evaluation of the algorithm’s current performance. Future improvements to the algorithm include:

1. **Integration of Sentiment Analysis**: To reduce the impact of unforeseen negative events on trades.
2. **Market Trend Detection**: To adapt signal generation strategies during bull or bear markets.
3. **Scalability**: Migration to AWS for improved flexibility and modularity.



