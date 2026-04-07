# Stock-Market-Analysis
Stock Market analysis using python ( pandas , seaborn , matplotlib )

#imported dataset of nifty 50 from yfinance

import yfinance as yf
df = yf.download("^NSEI", period="1y", interval="1d")
