Stock Picker

This Ruby method takes an array of stock prices and determines the best days to buy and sell to maximize profit.

- Parameters
'prices' (Array of Integers):
An array where each element represents the stock price on a given day.

- Usage
To use the 'stock_picker' method, provide an array of stock prices. The method will return an array containing the best day to buy and the best day to sell to maximize profit.

- Explanation

Initialization:
The method initializes 'best_buy_day', 'best_sell_day', and 'max_profit' to track the best days to buy and sell and the maximum profit encountered.

Iteration:
The outer loop iterates over each price as a potential buy price.
The inner loop iterates over the subsequent prices as potential sell prices.

Profit Calculation:
For each pair of buy and sell days, the method calculates the profit.

Profit Comparison:
If the calculated profit is greater than the current 'max_profit', the method updates 'max_profit', 'best_buy_day', and 'best_sell_day'.
Result:
The method returns an array containing 'best_buy_day' and 'best_sell_day'.
