# EA New Way MT5

This is a sample code for the EA New Way MT5, developed by the Forex Robot Easy Team. Please note that ForexRobotEasy is not the official developer of this product. We only provide this sample code as an example of how the EA can work.

For detailed reviews and trading results of the official EA New Way MT5, you can visit the following link: [EA New Way MT5 Review](https://forexroboteasy.com/forex-robot-review/ea-new-way-mt5-review-secure-purchase-bonus-guide/)

## Description

The EA New Way MT5 is a forex trading expert advisor that uses proprietary indicators to determine market trends and perform trading activities. It is designed to work on the MetaTrader 5 platform.

## Inputs

The EA New Way MT5 requires the following inputs:

- **LotSize**: The lot size for each trade. Default value is 0.01.
- **MaxOrders**: The maximum number of orders to place. Default value is 5.
- **Slippage**: The maximum allowed slippage in pips. Default value is 3.
- **MagicNumber**: The magic number to identify trades placed by the EA. Default value is 12345.

## Variables

The EA New Way MT5 uses the following variables:

- **totalOrders**: The total number of orders placed by the EA.
- **previousPrice**: The previous price of the currency pair.

## Expert initialization function

The `OnInit` function is called when the expert advisor is initialized. It initializes the necessary variables.

## Expert deinitialization function

The `OnDeinit` function is called when the expert advisor is deinitialized. It can be used to perform any necessary clean up tasks.

## Expert tick function

The `OnTick` function is called on every tick of the currency pair. It checks if a new candle has formed and if the price movement exceeds a threshold. If so, it determines the market trend using proprietary indicators and performs trading activities based on the trend.

## Determine market trend

The `DetermineTrend` function implements trading strategies using proprietary indicators to determine the market trend. It can use strategies like moving average crossover, breakout, or trend reversal. It returns a value indicating the determined trend (1 for uptrend, -1 for downtrend, 0 for no trend).

## Perform trading activities

The `PerformTradingActivities` function performs trading activities based on the determined trend. It checks if the maximum number of orders is reached and places buy or sell orders accordingly. It uses the lot size, current ask or bid price, slippage, and magic number as inputs for the OrderSend function. It also increments the total number of orders.

Please note that this is a simplified explanation of how the EA New Way MT5 works. The actual implementation may be more complex and may include additional features and functionalities.

For more information and to find the official developer of the EA New Way MT5, please use the MQL5 platform.
