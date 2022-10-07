# stock_trading_app
An app to buy and sell stocks using virtual currency, and track your investment portfolio
![image](https://user-images.githubusercontent.com/22425008/193263720-cf29809f-2079-4099-953e-643b74e366a6.png)

An app to buy and sell stocks using virtual currency, and track your investment portfolio. The app uses the IEX API to fetch stock price data.
The user has access to the following features:

# View holdings
On the main page, you can see your current sock & cash holdings as well as a visual pie chart representing your current portfolio. The chart is created using the Chart.js library by dynamically obtaining the values & values from the table view inside the index.js function and then generating a random colour for each value to be displayed in the pie chart. This generation happens on each page refresh.

# Buy
You can buy stocks by entering the stock symbol and number of shares. Before this, you may want to use the quote feature below to check the price.

# Quote
View current stock prices by looking up stocks by their symbol.

# Sell
Sell stocks by selecting the symbol fromt the list of owned stocks and number of shares you want to sell.

# View transaction history
View transaction history including price, date and number of shares bought for any transaction you have made before. The data is saved in an SQLite databse and saved on the server so history is maintained across sessions.
