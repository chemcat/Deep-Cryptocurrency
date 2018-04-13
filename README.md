# Deep-Cryptocurrency
Programming enviorment: Jupyter Notebook + Python 3.6

In this project, I'm working on using RNN(e.g. LSTM) to predict the price of cryptocurrency. 

Implement data_fetcher.ipynb first to generate a csv file storing a list of top 50 cryptocurrency tickers and their historical data. Note: depending on the exchange platform chosen, it might not be able to access all top 50 historical data. 

Then go to main.ipynb to load data and train/fit/evaluate the sequential model. I used Bitcoin recent 2 years data at 1hr interval as the input data. Price_open,volume and trades_count were selected as features. A customized accuracy with +/-1% prediction error tolerance was monitored as metrics along with loss. The highest accuracy on training samples reached above 30%. 

To continue increase the accuracy, I'll work on the following approaches ---just thinking loud here :)

~ News analysis with word embeding (may hard to define the influence of news on price on a hourly basis)

~ Possible bitcoin price coupling with other cryptocurrencies (e.g. volume of Tether)

~ sophisticate the sequential model

...TBD...





