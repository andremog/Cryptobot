# Cryptobot
This is an on-going project to create a useful bot for tracking your cryptocurrency portfolio.  

<b>Exchanges supported:</b> [CoinBase](https://www.coinbase.com "CoinBase Exchange")

<b>Info needed:</b> API key 

# Current features:
- List all transactions by coin
- Calculate profit/loss for each coin (value in USD, % change)
- Calculate profit/loss for entire portfolio
- Supports multiple accounts within Coinbase and allows manual input of external balances

# Future features:
- Support other exchanges ([Bittrex](https://www.bittrex.com "bittrex"), [Kraken Exchange](https://www.Kraken.com "Kraken Exchange"))
- Automate external balance import from other exchanges/[Coinigy](https://www.coinigy.com "Coinigy")

# Installation steps:

0. Open Terminal
1. Type ```sudo apt install python3-pip```
2. Type ```sudo pip3 install coinbase```
3. Log on [CoinBase](https://www.coinbase.com "What are you waiting for? Click me"). Navigate to Settings --> API Access --> + New API Key
4. Select the accounts you want to use the bot on and all permissions that end in ":read"
<img src="https://raw.githubusercontent.com/kwkevinlin/Cryptobot/master/images/Screen%20Shot%202017-08-14%20at%207.10.24%20PM.jpg" height="300">

5. Record your API public and secret key somewhere safe
6. Enter your API keys into config.json
7. Type ```python3 main.py``` in Terminal to run script

