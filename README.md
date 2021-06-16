# alphavantageapi

## function to access alphavantage intraday cryptocurrency prices api.

    Get a free API key here: https://www.alphavantage.co/ 
    
    ---- Arguments ----------------
    coin | the cryptocurrency coin ticker (str)
    granularity | the time interval between data points in minutes (1, 5, 15, 30, or 60) (int)
    
    
    ---- Returns ------------------
    df | a pandas dataframe, with columns: open, close, high, low, volume, percent_change, coin
    pyplot | line plot showing percentage change over time interval
