---
layout: single
title: "Wall-E"
tags: ["python", "bot", "telegram", "development", "stock", "markets", "scraping", "heroku", "API", "sentiment"]
---

Hi! In this entry I want to share a project I have been working on lately. It consists on a telegram bot whose contact is <em>@walleMurtagghh_bot<em>
and that I have called Wall-E.

In this first version of the project, the bot has a number of different functionalities. The majority and main of them consist of providing information related to the stock markets, where the information is extracted from the web using scraping techniques, mainly from the 
<a href = "https://es.finance.yahoo.com/">yahoo finance website</a>, an ideal portal for obtaining diverse and complete information on financial markets. In addition, Wall-E also provides other types of economic data such as the current value of the Euribor, the current inflation rate in Spain or the value of the EUR/USD exchange rate. In a complementary way, the bot allows to consult the information of the billboard of the local cinemas of my city of origin (Palencia, Spain) and some different functionalities such as the download in .mp4 format of videos from youtube or the generation of qr codes for a url introduced in a message. The last functionality added refers to sentiment analysis, allowing through the twitter API to see the sentimental state related to a term. For more information on the commands allowed in the bot, the /help command gives a more detailed and complete view of them. In future versions or updates of the code, other functionalities of a diverse nature will be included.

The project has been developed entirely with the Python language, using libraries such as Telebot for the implementation of the bot from Python, BeautifulSoup for the various web scraping processes performed, pytube for downloading videos from Youtube, tweepy for accessing the Twitter API or nltk for sentiment analysis, among other libraries.

The bot is uploaded on the free <a href = "https://dashboard.heroku.com/apps">Heroku</a> host page.

