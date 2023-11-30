# PZ Divergence Trading MT5

This code is an example of how to use the PZ Divergence Trading MT5 software. Please note that ForexRobotEasy is not the official developer of this product. We only provide a sample code that works as described in this product. To find the official developer of this product, please refer to MQL5.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/review-pz-divergence-trading-mt5-reliable-forex-software-for-traders/).

## Description

The PZ Divergence Trading MT5 is a reliable forex software designed to identify and trade divergences in the market. It utilizes various oscillators, such as the RSI, to detect divergences between price and the oscillator. Divergences are powerful trading signals that can indicate potential trend reversals or continuations.

The code provided demonstrates how to use the PZ Divergence Trading MT5 software in an Expert Advisor (EA) for MetaTrader 5. It includes the necessary libraries and classes to execute trades and calculate divergences. The code scans for regular and hidden divergences, and based on the generated signals, executes trades accordingly.

## How It Works

1. The code includes the necessary libraries and classes (`Trade` and `Indicators`) for executing trades and calculating divergences.

2. The necessary variables and objects are declared:
   - `CTrade trade`: Trade object for executing trades.
   - `CIndicator indicator`: Indicator object for calculating divergences.
   - `ENUM_INDICATOR oscillator`: Preferred oscillator chosen by the trader.

3. In the `OnInit` function, the preferred oscillator is set (`oscillator = INDICATOR_RSI`) and checked for validity. If the oscillator is invalid, an error message is printed, and the initialization fails.

4. The indicator is then initialized with the chosen oscillator. If the initialization fails, an error message is printed, and the initialization fails.

5. The parameters for scanning divergences and generating trading signals are set using the `SetDivergenceParameters` and `SetSignalParameters` functions.

6. In the `OnTick` function, the code checks for regular and hidden divergences using the `ScanDivergences` function.

7. If a divergence is detected, the entry and exit signals for trading positions are obtained using the `GetEntrySignal` and `GetExitSignal` functions.

8. Based on the signals, the code executes the appropriate trade using the `Buy`, `Sell`, `CloseBuy`, and `CloseSell` functions of the `trade` object.

9. In the `OnDeinit` function, the resources are cleaned up and released using the `Cleanup` function of the `indicator` object.

## Product Description

The PZ Divergence Trading MT5 is a reliable forex software designed to identify and trade divergences in the market. It uses various oscillators, such as the RSI, to detect divergences between price and the oscillator.

Key Features:
- Identifies regular and hidden divergences.
- Generates accurate entry and exit signals for trading positions.
- Can be used with different oscillators.
- Easy to use and integrate into an Expert Advisor.

The PZ Divergence Trading MT5 is a powerful tool for traders looking to take advantage of divergences in the market. Divergences can provide valuable insights into potential trend reversals or continuations, allowing traders to make informed trading decisions.

Please note that ForexRobotEasy is not the official developer of this product. We only provide a sample code that works as described in this product. To find the official developer of this product, please refer to MQL5.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/review-pz-divergence-trading-mt5-reliable-forex-software-for-traders/).
