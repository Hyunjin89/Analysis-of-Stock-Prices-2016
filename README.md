# Analysis-of-Stock-Prices-2016

In this data project we will focus on exploratory data analysis of stock prices. We'll focus on bank stocks and see how they progressed throughout the financial crisis all the way to early 2016.

Data
We need to get data using pandas datareader. We will get stock information for the following banks:

Bank of America
CitiGroup
Goldman Sachs
JPMorgan Chase
Morgan Stanley
Wells Fargo
Figure out how to get the stock data from Jan 1st 2006 to Jan 1st 2016 for each of these banks. Set each bank to be a separate dataframe, with the variable name for that bank being its ticker symbol. This will involve a few steps:

Use datetime to set start and end datetime objects.
Figure out the ticker symbol for each bank.
Figure out how to use datareader to grab info on the stock.
