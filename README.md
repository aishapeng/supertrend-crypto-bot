# supertrend-crypto-bot
Supertrend bot using python, pandas, and ccxt

Supertrend depicts the distinction between downtrends and uptrends.

The supertrend indicator calculation goes as stated below-

Up = (high + low / 2 + multiplier  x  ATR

Down = (high + low) / 2 – multiplier x ATR

### NOTE:
supertrend.py will place buy order when downtrend shifts to uptrend, and place sell order when uptrend shifts to downtrend.

# To run this Python script
1. Enter your Binance API Public key and Secret key in config.py. This is because the real-time market data will be pulled from Binance server usingg CCXT library.
2. pip -r requirements.txt to install necessary packages.
3. NOTE: The script will place actual orders on your Binance account. TRADE AT YOUR OWN RISK. 


