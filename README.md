# PoliticalStockWatch
Compared politicians Nancy Pelosi & Sheldon Whitehous VS S&P 500



# Libaries to import 
import pandas as pd,
import hvplot.pandas,
from MCForecastTools import MCSimulation,
import matplotlib as plt,
%matplotlib inline,
import numpy as np,
import yfinance as yf,
import datetime as dt,
from pandas_datareader import data,
import pandas_datareader as pdr,
import holoviews as hv,
from datetime import timedelta,
from pathlib import Path,
import seaborn as sns,
import pandas_montecarlo









# Group analysis 
FINAL REPORT
Sharpe Ratio:
Pelosi's 1 Year Sharpe Ratio: 132.55410874505054
Sheldon's 1 Year Sharpe Ratio: 194.03089760952793
SPY's 1 Year Sharpe Ratio: 229.84652886191716
Standard Deviation:
Pelosi's STD: 689.891492123228
Sheldon's STD: 553.3679365764682
SPY STD: 460.6908835519656
SPY has a better Risk/Return ratio than Pelosi's portfolio
Pelosi's stock portfolio is more volatile than the SPY
SPY has a better Risk/Return ratio than Sheldon's portfolio
Sheldon's stock portfolio is more volatile than the SPY
Sheldon's portfolio has a better Risk/Return ratio than Pelosi's
Pelosi's portfolio is more volatile than Sheldon's
Pelosi has the most volatile portfolio
SPY has the best Risk/Return Ratio
Republicans win, Sheldon has a better Risk/Return than Pelosi
BUT, even Sheldon couldn't beat the market. SPY had the best overall Risk/Return







# Functions used
1. .dropna()
	2. .pct_change()
	3. .var (variance)
	4. .cov() (covariance)
	5. .std (standard deviation)
	6. .mean()
	7. .hvplot()
	8. .cumprod()
	9. .concat()
	10.  .rolling() 11. .sort_values() 12. .montecarlo, plot(),.heatmap(),.corr()








# Overview 
Created multiple datasets and variables representing 2 politicians, Nancy Pelosi and Sheldon Whitehouse, and the SPY. We then used financial analysis functions in order to calculate and plot standard deviations, sharpe ratios, cumulative returns, etc. Used seaborn in order to visualize a heatmap of correlated stocks in a concatenated dataframe between Pelosi and SPY. Created conditional statements that allowed comparison between politicians and the SPY in order to make final conclusions











# HVPlot that ran in Juypter Notebook

Wanted to implement HVplot for these graphs(still usable for analyst)
![image](https://user-images.githubusercontent.com/106267420/182759056-a2244daa-3151-48c1-8e48-e5a276a90aa1.png)
![image](https://user-images.githubusercontent.com/106267420/182759090-3b19b60f-6697-4667-8871-a5eafa757521.png)
![image](https://user-images.githubusercontent.com/106267420/182759132-72802ab3-2b15-4494-8eeb-86dd8316fae3.png)
![image](https://user-images.githubusercontent.com/106267420/182759195-346cd274-d75e-4f29-aae0-f416bb7af0cc.png)
![image](https://user-images.githubusercontent.com/106267420/182984624-29db8b28-2ce0-45b6-8e70-9feaec8c6e42.png)
![image](https://user-images.githubusercontent.com/106267420/182984966-d9452697-88e4-4094-9269-06fffeb3b13c.png)
![image](https://user-images.githubusercontent.com/106267420/182985008-89b4f9d3-96da-4aee-b5e3-136e2210f80e.png)


