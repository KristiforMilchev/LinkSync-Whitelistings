![](https://linksync.tech/wallet/0.png)


### **What is the purpose of this repository?**

The main purpose of the repository is to whitelist cryptocurrency assets on the SYNC ecosystem, it is maintained by the LinkSync team and there 
are no payments required in order to get listed on our system however there are requirements that each token has to meet. Once your token is approved and merged with the main branch your
token data will be accessible across the entire Linksync ecosystem which includes but is not limited to:

* SYNCWallet 
* SYNC Tracker
* SYNC Pay for business that decide to allow your token on the payment filters
* SYNC Charts once we are ready to ship it.
* SYNC Price bots
* SYNC Real time Transaction bot

That being said, your token is still supported by the SYNC ecosystem in case it's not officially listed but we will only track limited
information and display a warning to all users that they are looking at a token that is not whitelisted on our system. Tokens that aren't whitelisted 
don't get real time price tracking, social media feed tracking and historical data.

### **What is the whitelist criteria?**


* ``Market Capital bigger then $ 100 000 ``
* ``Official website older then 4 months `` 
* ``Social media accounts (Twitter, Facebook or Instagram) minumum of 500 real followers ``
* ``Realistic roadmap ``
* ``Listed on on least one major exchange or commonly used defi exchange such as Pancackeswap, Sushiswap or Uniswap. ``
* ``Must be on an EVM compatible blockchain e.g BSC, ETH, Polygon and other derivitives. ``


### **How to add your own token to the eco system?**

if you're project fits the requirements for our eco system then the only thing that you need to do is clone the repository, checkout a new branch with the following naming convention
``listing_tokenname`` inside the folder Whitelist create a folder with your token name (Not the symbol) follow the following convention e.g Binance Smart Chain (BinanceSmartChain) inside the new folder
add the following file named token.json replace all the fields with the information regarding your own token then open a pull requests to merge with the main branch. After you open the pull requests for a merge you must follow the instructions from the github bot and tweet at us on twitter with the following message ```Joing the #SYNCFamily :) #yourtokenname```

```
{
  "Name": "LinkSync",
  "Symbol": "SYNC",
  "Website": "https://linksync.tech",
  "Description": "LinkSync aims to provide a safe trading environment to early crypto investors by designing an online platform that restricts access to scam projects while giving increased visibility and in- sights on promising projects. Our teams of experts will evaluate KYC, PoC, white papers, smart contracts and many more.",
  "Logo": "https://linksync.tech/assets/PNG/Letermark_Color.png",
  "Contracts": [
    {
      "Network": 2,
      "Decimals": 9,
      "ContractAddress": "0xf6a22b0593df74f218027a2d8b7953c9b4542aa1",
      "Supply": "1000000000000000",
      "MainLiquidityPool": "0x1c06a11e94B5502d011Bbd240F23d1c147561DAb",
      "PairTokenAddress": "0xbb4CdB9CBd36B01bD1cBaEBF2De08d9173bc095c",
      "ListedExchangeRouter": "0x10ED43C718714eb63d5aA57B78B54704E256024E",
      "PairName":"BNB"
    }
  ],
  //Ds source -0 Facebook, -1 Twitter, -2 Telegram, -3 Exchange -4 Website, -5 Reddit
  "Links": [
    {
      "Type": 0,
      "Name": "Linksyncofficial",
      "Url": "https://www.facebook.com/Linksyncofficial"
    },
    {
      "Type": 1,
      "Name": "LinkSync_Tech",
      "Url": "https://twitter.com/LinkSync_Tech"
    },
    {
      "Type": 2,
      "Name": "@linksyncofficial",
      "Url": "https://t.me/linksyncofficial"
    },
    {
      "Type": 3,
      "Name": "Pancakeswap",
      "Url": "https://pancakeswap.finance/swap?outputCurrency=0xF6a22B0593df74F218027A2d8b7953c9b4542AA1"
    },
    {
      "Type": 4,
      "Name": "Website",
      "Url": "https://linksync.tech/"
    },
    {
      "Type": 5,
      "Name": "r/Linksync_Army",
      "Url": "https://www.reddit.com/r/Linksync_Army/"
    }
  ],
   "TwitterFeed":"Added by SYNC Team do not change",
  "InstagramFeed":"Added by SYNC Team do not change",
  "YoutubeFeed":"Added by SYNC Team do not change"
}

```

Important, listing tokens can take some time while the team validates the information entered inside the request and we refrain 
the right to deny access to certain projects in case there are evidence of fraud or other malicious intent.

You can buy me a coffee if you want here: 
```0x09b26ff91DfB5b959908fd7f6cEe73e19FA75817```– Crypto
