# Binance_trade_autamatization
Trade on binance using twitter with python.

Please do not use this code if you don't understand at all what is happening, your crypto (meanning your money) could be compomised. In order to avoid any problems I have separate the trade part from the main code.

This code is creating a tunnel beetwenn Binance an Twitter, you can easly change one of those plateforms for another (facebook instead of twitter for example). You can easily change the condition of a trade and the twitter's account your scrapping data from.
This project is using twitter's and binance's API and you will need a developper acces for twitter in order to get your BEAR-TOKEN and different consummer and acces key/token. In binance you will also have to create a API in order to get your config.apiSecurity and config.key. In order to get acces to both of those API here are 2 usefull links : (Binance : https://www.binance.com/en/support/faq/360002502072) (Twitter : https://developer.twitter.com/en/docs/twitter-api/getting-started/getting-access-to-the-twitter-api)
WARNING you mustn't give any of your keys to anyone, otherwhise anybody would have total acces your different accounts

You will need to have PIP install on your computer, and different lib (argparse / tweepy / Binance.client / textblob) they facilitate a lot our task. In order to install a lib you must run : pip install name of the lib
