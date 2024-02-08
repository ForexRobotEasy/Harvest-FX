# Harvest FX

This code is developed based on the assignment - 'Terms of Reference for Writing Code for Product Harvest FX'. It aims to create a Forex trading system using the Trend Wave Indicator to identify trend movements, an oscillator to spot overbought and oversold zones, and three robust strategies for smart entries. The system is compatible with small accounts and has adjustable parameters for customization.

## Indicator Parameters

### Trend Wave Indicator parameters
- `ZZ_Depth` : Depth of the ZigZag indicator
- `ZZ_Deviation` : Deviation of the ZigZag indicator
- `ZZ_Backstep` : Backstep of the ZigZag indicator

### Oscillator parameters
- `ADX_Period` : Period for calculating the ADX indicator
- `Dynam` : Dynam value for the ADX indicator

## Expert Logic

### Custom indicator initialization function
The `OnInit()` function is responsible for initializing the custom indicator.

### Opening Positions
The `OnTick()` function contains the logic for opening positions.

### Closing Positions
The `OnDeinit()` function contains the logic for closing positions.

## Usage

To use this code, you need to have the MetaTrader 5 platform installed. Once installed, follow the steps below:

1. Open MetaEditor in the MetaTrader 5 platform.
2. Create a new Expert Advisor.
3. Copy and paste the code into the Expert Advisor file.
4. Save the file with a suitable name.
5. Compile the code by clicking on the 'Compile' button or pressing F7.
6. Attach the Expert Advisor to a chart in the MetaTrader 5 platform.
7. Adjust the indicator and oscillator parameters according to your preferences.
8. Start the Expert Advisor to execute the trading system.

## Product Description

This code provides a Forex trading system called Harvest FX. It utilizes the Trend Wave Indicator to identify trend movements and an oscillator to spot overbought and oversold zones. The system has three robust strategies for smart entries, making it suitable for both beginner and experienced traders.

The Harvest FX trading system is designed to be compatible with small accounts and offers adjustable parameters for customization. It aims to provide consistent and profitable trading opportunities in the Forex market.

Please note that ForexRobotEasy is not the official developer of this product. We only provide sample code that can work as described in this product. To find the official developer of this product, please refer to the MQL5 platform.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy - Harvest FX Review](https://forexroboteasy.com/forex-robot-review/harvest-fx-review-smart-forex-trading-with-trend-wave-indicator/).
