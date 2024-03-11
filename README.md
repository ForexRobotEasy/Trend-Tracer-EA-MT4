# Trend Tracer EA MT4

This Expert Advisor (EA) is designed to identify and trade market trends in the MetaTrader 4 (MT4) platform. It is developed by Forex Robot Easy Team and more information about this product can be found on their website [here](https://forexroboteasy.com/forex-robot-review/trend-tracer-ea-mt4-review-optimal-for-trendy-market-conditions/).

## Functionality

The Trend Tracer EA uses a simple trend-following strategy to open buy or sell orders based on the current market trend. It calculates the stop loss and take profit levels based on user-defined percentages of the current price. The EA works with any currency pair and timeframe.

## Installation

To use this EA, follow these steps:

1. Download the Trend Tracer EA MT4 file.
2. Open the MT4 platform and go to 'File' -> 'Open Data Folder'.
3. Copy the EA file into the 'MQL4/Experts' folder.
4. Restart the MT4 platform.
5. Go to the 'Navigator' panel and expand the 'Expert Advisors' folder.
6. Drag and drop the Trend Tracer EA onto the desired chart.

## Configuration

The Trend Tracer EA has the following configurable parameters:

- **trendPeriod**: The period used to identify the market trend. Default value is 14.
- **riskPercentage**: The percentage of account equity to risk per trade. Default value is 2.0.
- **stopLossPercentage**: The percentage of the current price used as the stop loss level. Default value is 1.0.
- **takeProfitPercentage**: The percentage of the current price used as the take profit level. Default value is 2.0.

## How it works

1. The EA checks the current price of the selected symbol using the `MarketInfo` function.
2. It determines the market trend by comparing the current price with the previous price using the `IsUptrend` and `IsDowntrend` functions.
3. If the market is in an uptrend, it calculates the stop loss and take profit levels based on the user-defined percentages.
4. It opens a buy order using the `OrderSend` function with the calculated stop loss and take profit levels.
5. If the market is in a downtrend, it calculates the stop loss and take profit levels based on the user-defined percentages.
6. It opens a sell order using the `OrderSend` function with the calculated stop loss and take profit levels.

## Disclaimer

Please note that Forex Robot Easy Team is not the official developer of this product. This code is only provided as a sample that can work as described in their product. To find the official developer of this product, please use MQL5.

For detailed reviews and trading results of this product, please visit the [Forex Robot Easy website](https://forexroboteasy.com/forex-robot-review/trend-tracer-ea-mt4-review-optimal-for-trendy-market-conditions/).
