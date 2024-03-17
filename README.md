# FSM_Chatbot_for_Stock_Information_Queries
In this project, a basic chatbot for stock information queries was built by using NLP (Natural Language Processing) knowledge. The program were firstly constructed and run using python on JupyterLab during to its aesthetic and interactivity, then it was completed, perfected on Spyder and the final step was to test its performance on Wechat. Several methods and algorithms including those obtained from extension python modules were used to build the main framework.

## Demonstration GIF
![image](https://github.com/HaojieChu/FSM_Chatbot_for_Stock_Information_Queries/blob/main/Wechat%20Demo%20GIF.gif)
## Packages Installation
### [Rasa NLU]
Rasa is an open source machine learning framework to automate text-and voice-based conversations. With Rasa, you can build chatbots on:
- Facebook Messenger
- Slack
- Microsoft Bot Framework
- Rocket.Chat
- Mattermost
- Telegram
- Twilio
- Your own custom conversational channels  

And Rasa NLU (Natural Language Understanding) is a tool for understanding what is being said in short pieces of text.  
For example, taking a short message like:  
```
"I'm looking for a Mexican restaurant in the center of town"   
```
And returning structured data like:  
```
intent: search_restaurant  
entities:  
  - cuisine : Mexican  
  - location : center  
```

Using pip to install Rasa NLU via Python Library From pypi:  
```
pip install rasa_nlu
```
**For more installation information of Rasa NLU**  
Please click on https://rasa.com/docs/rasa/user-guide/installation/ 



### [iexfinance]
The iexfinance is a Python module help you get data for Stocks, ETFs, Mutual Funds, Forex/Currencies, Options, Commodities, Bonds, and Cryptocurrencies from IEX Cloud and IEX API:
- Real-time and delayed quotes
- Historical data (daily and minutely)
- Financial statements (Balance Sheet, Income Statement, Cash Flow)
- End of Day Options Prices
- Institutional and Fund ownership
- Analyst estimates, Price targets
- Corporate actions (Dividends, Splits)
- Sector performance
- Market analysis (gainers, losers, volume, etc.)
- IEX market data & statistics (IEX supported/listed symbols, volume, etc)
- Social Sentiment and CEO Compensation

Using pip to install iexfinance via Python Library From pypi (latest stable release): 
```
pip3 install iexfinance
```

An IEX Cloud account is required to acecss the IEX Cloud API. Various plans are availalbe, free, paid, and pay-as-you-go.  
Your IEX Cloud (secret) authentication token can be passed to any function or at the instantiation of a `Stock` object. The easiest way to store a token is in the `IEX_TOKEN` environment variable.  

***Real-time Quotes***  
To obtain real-time quotes for one or more symbols, use the `get_price` method of the `Stock` object:  
```
from iexfinance.stocks import Stock  
tsla = Stock('TSLA')  
tsla.get_price()  
```
***Historical Data***  
It’s possible to obtain historical data using `get_historical_data` and `get_historical_intraday`.

**For more installation information of iexfinance**  
Please click on https://github.com/addisonlynch/iexfinance  

**For more information about iexfinance**  
Please click on https://pypi.org/project/iexfinance/  



### [wxpy]  
The wxpy is a python module and it was a updated version of itchat. By installing it, many functions related to Wechat APP such as sending messages or pictures, automatically replying messages of various types can be achieved.  

Using pip to install wxpy via Python Library From pypi (latest stable release): 
```
pip install -U wxpy
```
**For more information about wxpy**  
Please click on https://github.com/youfou/wxpy to visit its official Github webpage


## Contact the Author  

If you got any enquiries or suggestions, I'm all ears :sunglasses:  

- **Institution:**  University of Malaya  :mortar_board: Data Science Graduate  
- **Author** Haojie Chu
- **Academic E-mail:** hjchuyu5@gmail.com
