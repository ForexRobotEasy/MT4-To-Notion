# MT4 To Notion - Trading Robot

This code is a trading robot that exports trade data from MetaTrader 4 (MT4) to Notion, a collaborative note-taking and task management tool. It allows traders to streamline their forex trades by automatically exporting trade information to Notion.

## Developer

This trading robot is developed by the Forex Robot Easy Team. Please note that ForexRobotEasy is not the official developer of this product. We only provide a sample code that can work as described in this product. To find the official developer of this product, please use MQL5.

## Developer's Site

For detailed reviews and trading results of this product, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/mt4-to-notion-review-streamline-forex-trades-with-ease/).

## Import Libraries

The necessary libraries for this code are imported using the `#include` directive.

## Trade Export Fields

The trade export fields are defined using an enumeration called `TradeFields`. These fields include the type of trade, volume, symbol, open price, close price, and profit.

## Trade Data Structure

A data structure called `TradeData` is defined to store the trade information. It includes the trade type, volume, symbol, open price, close price, and profit.

## Export Trades to Notion

The `ExportTradesToNotion` function is responsible for exporting trades to Notion. It takes two parameters - `timeRange` and `fields`. The `timeRange` parameter determines the time range from which to retrieve the trades, and the `fields` parameter specifies the trade fields to export. The function retrieves the trade data from the trading account based on the specified time range and exports the trade information to Notion.

## Get Trades from Last Day, Week, Month, or Custom Time Range

There are four functions - `GetTradesFromLastDay`, `GetTradesFromLastWeek`, `GetTradesFromLastMonth`, and `GetTradesFromCustomTimeRange` - that retrieve trades from the trading account based on different time ranges. These functions return an array of `TradeData` structures containing the retrieved trade information.

## Get Trade Information

The `GetTradeInfo` function takes a `TradeData` structure and an array of `fields` as parameters. It generates a string that contains the trade information based on the specified fields. The function iterates through the `fields` array and appends the corresponding trade information to the `tradeInfo` string.

## Send Trade Information to Notion

The `SendToNotion` function takes a `tradeInfo` string as a parameter and sends the trade information to Notion. The actual code to send the information is not provided and should be implemented separately.

## Initialization and OnTick Functions

The `OnInit` function is the entry point of the program. It initializes the MT4 to Notion software. The `OnTick` function is called on each tick and checks if a trade is closed. If a trade is closed, it retrieves the closed trade and sends the trade information to Notion.

## Trade Is Closed and Get Closed Trade Functions

The `TradeIsClosed` function checks if a trade is closed. The actual code to check the trade status is not provided and should be implemented separately. The `GetClosedTrade` function retrieves the most recently closed trade from the trading account. The actual code to retrieve the closed trade is not provided and should be implemented separately.

Please note that the code provided is a sample and may need to be modified and extended to work with your specific trading setup and Notion integration.

For detailed reviews and trading results of this product, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/mt4-to-notion-review-streamline-forex-trades-with-ease/).
