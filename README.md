# mql5 Big Figure Indicator ReadMe

This code is an implementation of the Big Figure Indicator for MetaTrader 5 (MT5). The Big Figure Indicator is used to mark significant round numbers on a forex chart.

## Indicator Details

- Name: Big Figure Indicator MT5
- Developer: Forex Robot Easy Team
- Website: [Forex Robot Easy](https://www.forexroboteasy.com)
- Indicator Color: Red

## Indicator Settings

- Indicator Window: Chart Window
- Indicator Buffers: 1

## Indicator Initialization

The `OnInit` function initializes the indicator by setting the indicator buffer.

## Indicator Calculation

The `OnCalculate` function is the main calculation function for the indicator. It checks if the current timeframe is within the specified range (M1 to H8) and calculates the significant round numbers based on the current instrument's digits. The significant levels are marked with horizontal lines on the chart.

## Product Description

This code provides a sample implementation of the Big Figure Indicator for MetaTrader 5. The indicator helps traders identify significant round numbers on forex charts, which can act as support or resistance levels. This can be useful for making trading decisions and setting profit targets.

Please note that Forex Robot Easy is not the official developer of this product. We only provide this sample code that can work as described in the product. To find the official developer of this product, please use MQL5.

For detailed reviews and trading results of this product, please visit the [Big Figure Indicator MT5 Review](https://forexroboteasy.com/forex-robot-review/big-figure-indicator-mt5-review-precise-forex-chart-levels/) on Forex Robot Easy.
