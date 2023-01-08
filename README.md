https://colab.research.google.com/github/ClovisL/FidelityOptionsTracker/blob/main/FidelityOptionsTracking.ipynb

A Python script utilizing Pandas that reads a CSV file from Fidelity of trading history, creates a dataframe of only options trades, and exports an excel file.

The transaction date, ticker, whether it was a call/put, expiration date, strike price, quantity, and total $ amount are filtered and added to a new data frame to export into an excel spreadsheet, where further analysis through pivot tables may be done.

I wrote this program to better help me keep track of my trade history through a more convenient format than what is available through Fidelity's website, allowing me to view my past performance based on ticker and types of trades.
