# Mean Reversion Momentum Strategy

## Overview

The Mean Reversion Momentum Strategy is a trading strategy designed to capitalize on market inefficiencies by utilizing both mean reversion and momentum indicators. This strategy analyzes stock price movements to identify potential buy and sell signals, helping traders make informed decisions based on historical data.

## Features

- **Technical Indicators**: Utilizes various technical indicators such as Exponential Moving Average (EMA), Relative Strength Index (RSI), Bollinger Bands, and Volume-Weighted Average Price (VWAP) for comprehensive market analysis.
- **Backtesting**: Provides a framework for backtesting the strategy against historical stock data to evaluate performance and risk metrics.
- **Data Visualization**: Includes tools for visualizing strategy performance, allowing users to assess returns and drawdowns.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ali-3-3-3/MeanReversion-Momentum-Strategy.git
   cd MeanReversion-Momentum-Strategy
   ```

2. Install required dependencies (See: Install statements in code)

## Usage

1. Load historical stock data using Yahoo Finance or another data source.
2. Configure the parameters for the strategy (e.g., EMA windows, RSI levels).
3. Run the strategy backtest using the provided functions.
4. Analyze the results through the generated visualizations.

```python
import pandas as pd
from your_strategy_module import backtest_strategy

# Example of loading data and running the strategy
data = pd.read_csv('your_historical_data.csv')
results = backtest_strategy(data)

# Visualize results
results.plot()
```

## Technical Indicators

- **EMA**: Fast and slow exponential moving averages to identify trends.
- **RSI**: Measures the speed and change of price movements, helping to identify overbought or oversold conditions.
- **Bollinger Bands**: Provides a range of price movement and helps identify potential reversal points.
- **VWAP**: Average price weighted by volume, giving insight into the average trading price over a specific time period.

## Contributing

Contributions are welcome! If you have suggestions for improvements or want to add new features, feel free to submit a pull request or open an issue.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
