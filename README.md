# Simple Order Forex Software

This is a code for a Simple Order Forex Software developed by the Forex Robot Easy Team. Please note that ForexRobotEasy is not the official developer of this product, and this code is only a sample that can work as described in the product.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/simple-order-forex-software-review-quick-easy-pending-orders/).

## Description

The Simple Order Forex Software enables traders to place pending orders quickly and efficiently in the Forex market. It provides a user-friendly interface for order placement, modification, and adjustment of stop loss and take profit levels.

## Global Variables and Constants

- `StopLoss` (default: 50.0): Specifies the default stop loss size.
- `TakeProfit` (default: 100.0): Specifies the default take profit size.

## Initialization Function

The `OnInit` function is called when the code is initialized. It initializes the pending order panel by calling the `InitPanel` function.

## Deinitialization Function

The `OnDeinit` function is called when the code is deinitialized. It deinitializes the pending order panel by calling the `DeinitPanel` function.

## Panel Initialization Function

The `InitPanel` function creates a panel object and sets its properties. It adds buttons for order names (Buy and Sell) and displays the panel.

## Panel Deinitialization Function

The `DeinitPanel` function removes the panel from the chart.

## Handling Double-Click Event Function

The `OnChartEvent` function is called when a double-click event occurs. It checks if the double-click event occurred on a price level object. If yes, it prompts the user to confirm order placement. If the user confirms the order placement, it gets the button clicked on the panel and places the corresponding pending order.

## Get the Button Clicked on the Panel

The `GetButtonClicked` function is a placeholder that should be replaced with the actual implementation to get the button clicked on the panel.

## Place a Pending Order at a Price

The `PlacePendingOrder` function is a placeholder that should be replaced with the actual implementation to place the pending order using the specified order type and price.

## Adjust the Size of Stop Loss and Take Profit

The `AdjustStopLossTakeProfit` function is a placeholder that should be replaced with the actual implementation to adjust the stop loss and take profit levels.

## Main Program Function

The `OnStart` function is the main program loop. It checks for user input or other events by calling the `CheckEvents` function and performs other trading activities.

## Check for User Input/Events

The `CheckEvents` function is a placeholder that should be replaced with the actual implementation to check for user input or other events.

## Product Description

The Simple Order Forex Software is a user-friendly tool developed by the Forex Robot Easy Team. It allows traders to quickly and efficiently place pending orders in the Forex market. With a simple and intuitive interface, traders can easily modify and adjust stop loss and take profit levels.

Key Features:
- Quick and efficient pending order placement
- User-friendly interface for easy order modification
- Adjust stop loss and take profit levels with ease

Please note that this code is a sample provided by ForexRobotEasy. To find the official developer of this product, please use MQL5. For detailed reviews and trading results, visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/simple-order-forex-software-review-quick-easy-pending-orders/).
