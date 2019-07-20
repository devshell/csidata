# csidata

I am looking to build a Python wrapper for CSI Data to do the following:


1. Pull ALL historical data available in CSI Data to populate an empty db (date, open, high, low, close, and volume) - options would be to specify the market (i.e. pull all stocks, or all futures (incl. continuous), or all forex)

2. Pull PREVIOUS TRADING DAY's data from CSI Data to add a db record or overwrite existing data (date, open, high, low, close, and volume) - options would be to specify the market (i.e. pull all stocks, or all futures (incl. continuous), or all forex)

3. Pull ALL history for ONE symbol (i.e. pull all stocks, or all futures (incl. continuous), or all forex) and populate an empty db with info same as above, with option to overwrite existing db data for that symbol if it exists, otherwise output error (date, open, high, low, close, and volume) 

4. Pull PREVIOUS TRADING DAY's data for ONE symbol (i.e. pull all stocks, or all futures (incl. continuous), or all forex) to add a db record or overwrite existing data (date, open, high, low, close, and volume) 
