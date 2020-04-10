# PSEi Historical Data
Gets data from [PSEi RESTful API](http://phisix-api4.appspot.com)

This is initially a fork from my other project, PSE Stock Alert found [here](https://github.com/jderrickguarin/pse_stock_alert). The goal of this project is to gather data of historical closing prices of PSEi listed stocks (or the blue chip stocks). Everything, so far is written in Python as it is the simplest way for me incorporate the script to my data science, machine learning and finance pursuits. Since the original PSE API is faulty and is probably dead, I shifted my source to the PSEi RESTful API created by Edge Dalmacio (Github repository [here](https://github.com/edgedalmacio/phisix)). 

Data from this API only spans at least from 2016 to present, so I intend to scrape historical data, or look for it online, and make it freely available to the public through this repository. Another problem of the API is that its json formatted data only returns one price data, which I assume to be the closing price. No other data is included like open price, high, low, among others. Hopefully, this can be solved when I find a better, cheaper data source. 

Expect this readme file to be updated every once in a while as the project progresses. In the future, I might write a pip-installable python package that can generate csv files of historical prices given the company name and the data, or generate a pandas DataFrame of historical prices to help your data science projects. 
