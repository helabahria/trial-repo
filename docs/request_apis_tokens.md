### Social networks


- #### Facebook configuration


  To create a Facebook app you should visit [official developer.facebook.com website](https://developers.facebook.com/apps/) and respect the following steps:

  # Create an app

![alt text](img/1.png)


  # Confirm app creation


![alt text](img/2.png)



  # Get Facebook credentials

![alt text](img/3.png)



  # Get Facebook version


![alt text](img/4.png)


PS: 
All this credentials refers to APPID,APP_SECRET,FB_GRAPH_VERSION in .env file

```sh
APPID=process.env.APPID
APP_SECRET=process.env.APP_SECRET
FB_GRAPH_VERSION=process.env.FB_GRAPH_VERSION
```

- #### Google configuration

  To create a google app you should visit [official console.developers.google.com website](https://console.developers.google.com/) and respect the following steps:

  # Create Credentialds

![alt text](img/11.png)


  # Fill out the form

![alt text](img/22.png)



  # Get Client crededentials

![alt text](img/33.png)



  # Create Youtube configuration

  ![alt text](img/111.png)



  # Get Youtube configuration

  ![alt text](img/222.png)





PS: 
All this credentials refers to GOOGLE_CLIENTID,GOOGLE_CLIENT_SECRET and GDA_TAP_API_KEY in .env file

```sh
GOOGLE_CLIENTID=process.env.GOOGLE_CLIENTID
GOOGLE_CLIENT_SECRET=process.env.GOOGLE_CLIENT_SECRET
GDA_TAP_API_KEY= process.env.GDA_TAP_API_KEY
```


- #### LinkedIN configuration

  To create a linkedin app you should visit [official developer.linkedin.com website](https://developer.linkedin.com/) and respect the following steps:

  # Create a new app

![alt text](img/333.png)


  # Get linkedin crededentials

![alt text](img/444.png)




PS: 
All this credentials refers to LINKEDIN_KEY and LINKEDIN_SECRET in .env file

```sh
LINKEDIN_KEY=process.env.LINKEDIN_KEY
LINKEDIN_SECRET=process.env.LINKEDIN_SECRET
```




- #### Twitter  configuration

  To create a linkedin app you should visit [official  developers.twitter.com website](https://developer.twitter.com/) and respect the following steps:

  # Create a new app

![alt text](img/1t.png)


  # Set params for your app

![alt text](img/2t.png)



  # Get your twitter credentialds

![alt text](img/3t.png)



  # Get your twitter credentialds

  you can regenerate again your credentials with more options


![alt text](img/4t.png)




PS: 
All this credentials refers to TWITTER_CONSUMER_KEY_ALT, TWILTTER_CONSUMER_SECRET_ALT,TWITTER_CONSUMER_SECRET_DEV,TWITTER_CONSUMER_KEY
TWITTER_CONSUMER_SECRET,TWITTER_ACCESS_TOKEN_KEY and TWITTER_ACCESS_TOKEN_SECRET in .env file

```sh
TWITTER_CONSUMER_KEY_ALT=process.env.TWITTER_CONSUMER_KEY_ALT
TWILTTER_CONSUMER_SECRET_ALT=process.env.TWILTTER_CONSUMER_SECRET_ALT
TWITTER_CONSUMER_SECRET_DEV=process.env.TWITTER_CONSUMER_SECRET_DEV
TWITTER_CONSUMER_KEY=process.env.TWITTER_CONSUMER_KEY
TWITTER_CONSUMER_SECRET=process.env.TWITTER_CONSUMER_SECRET
TWITTER_ACCESS_TOKEN_KEY=process.env.TWITTER_ACCESS_TOKEN_KEY
TWITTER_ACCESS_TOKEN_SECRET=process.env.TWITTER_ACCESS_TOKEN_SECRET
```

- #### Telegram configuration


  To create a Telegram bot you should set it via mobile Telegram application:

  # BotFather

![alt text](img/bot1.png)


  # Get your confirmation

![alt text](img/bot2.png)



PS: 
This credential refer to TELEGRAM_BOT_TOKEN in .env file



```sh
TELEGRAM_BOT_TOKEN=process.env.TELEGRAM_BOT_TOKEN

```



- #### CoinMarketCap


 We get data refer tou Satt token from [official  coinmarketcap.com/api website](https://coinmarketcap.com/api/) and respect the following steps:




  # Create your account

![alt text](img/marketcap0.png)



  # Get your crededentials

![alt text](img/marketcap1.png)
