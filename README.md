<img src="Title.PNG">

# Stock data APIs in Python

## Prerequistes
Python 3.5+  
Jupyter Notebook Python 3  

## Dependencies  
* yfinance  
* TensorFlow 1.10.0  
* Pandas  
* Numpy  
* ta-lib  
* matlibplot  
* sklearn    
 
______________________________________________________________________________________________________________________________
## Examples 
```python

import numpy as np
import pandas as pd
import matplotlib.pyplot as plt

import warnings
warnings.filterwarnings("once")

import fix_yahoo_finance as yf
yf.pdr_override()

df = yf.download('MSFT','2018-01-01','2020-07-31')
df.head()
```


## Reading Material
https://www.investopedia.com/terms/s/stock-analysis.asp (Basic Stock Analysis)

https://www.investopedia.com/articles/investing/093014/stock-quotes-explained.asp (Understand Stock Data)

https://www.investopedia.com/terms/t/trendline.asp (Understand Trendline)
