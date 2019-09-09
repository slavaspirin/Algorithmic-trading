# RSI ETF Strategy #


Here we'll try to implement one of many very popular hedge fund strategies by creating a portfolio of an ETF and it's underlying stocks. I am going to create an algorithm that tracks every single stock from the ETF and manages portfolio by moving capital between ETF itself and underlying stocks. The main trigger of buying/selling stocks is based on Relative Strength Index (RSI) indicator. 


#### Considerations ####
- Dividends.  The model has to calculate dividends properly according to ex, record dates etc
- Reinvestment capital. Cash balance is recalculated every single day and being used for every next trade
- Transaction fees. Adjustable parameter.
- Management fees. Adjustable parameter. Takes a certain % of the portfolio every year.
- RSI signals. Based on adjustable parameters. 
- Holdings rebalancing. Create an algorithm to rebalance the weights as shares are being bought/sold 

**Continue [HERE](https://nbviewer.jupyter.org/github/SlavOK400/Algorithmic-trading/blob/master/algorithmic%20trading%20system.ipynb)**

<img src="readme_intro_pic.jpg"> 

