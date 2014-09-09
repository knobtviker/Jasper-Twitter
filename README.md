#Jasper-Twitter
==============

###Twitter module for JASPER.
###Allows the ability to check notifications(direct messages, retweets and mentions), send a tweet and check whats trending!

###steps to install Twitter.py
* Run
```
sudo pip install tweepy
```
* Go to https://apps.twitter.com/ and make a twitter application for jasper
* Give yourself read and write permissions(CRITICAL OR WONT BE ABLE TO TWEET/CHECK DIRECT MESSAGES)
4. Add the API key, API secret, Access token, Access token secret to profile.yml in jasper/client
```
CLIENT_SECRET: <API key>
TW_CONSUMER_KEY: <API KEY>
TW_CONSUMER_SECRET: <API SECRET>
TW_ACCESS_TOKEN: <ACCESS TOKEN>
TW_ACCESS_TOKEN_SECRET: <ACCESS TOKEN SECRET>
```
* In your home directory, run
```
git clone https://github.com/marclave/Jasper-Twitter.git
```
* Copy the Twitter.py file from Jasper-Twitter into jasper/client/modules

* Add to __init.py
```
from modules import Twitter
```
You have installed the Twitter module for jasper!

###Here are examples of what you can do with this module!
```
JASPER: How can I be of service?
YOU: Check what is trending in twitter
JASPER: #KepoAlaBetawi
JASPER: #HappyBeliebersDayAllAroundTheWorld
JASPER: #LosFinalistasGENERACIONESC
JASPER: #RuinThe90s
JASPER: #SiRegresaraEnElTiempoYo
YOU: Do I have any twitter Notifications
JASPER: You have no retweets
JASPER: Latest Mentions are
JASPER: @MarcLaventure You need to stop programming so much from JordanVlieg
JASPER: You have no Direct Messages
YOU: Send tweet
JASPER: What would you like to tweet?
YOU: @JordanVlieg :P
```
