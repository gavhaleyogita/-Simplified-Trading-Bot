# -Simplified-Trading-Bot
APPLICATION TASK
Build a Simplified Trading Bot
Register and activate a Binance Testnet account 
Generate API credentials 
Use the testnet base URL for all API interactions: https://testnet.binancefuture.com
Use python-binance library or REST calls to place orders 
Structure your code for reusability and clear input/output handling 
Log API requests, responses, and errors 
(Optional) Add support for advanced order types (e.g., Stop-Limit, OCO)

from binance import Client
class BasicBot:
 def __init__(self, api_key, api_secret, testnet = True):
 self.client = Client(api_key, api_secret)
 
