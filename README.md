# AlpacaTradingApp

This is a paper-trading application that utilizes Alpaca's API's and user authentication system. The API keys are kept private through the use of a PostGreSQL database. I created my own API for matching company names with their symbols. There are no free API's that serve this purpose so I created my own through webscraping using BeautifulSoup and Heroku's PostGreSQL server.

The front end is written in Javascript utilizing Vue and Quasar.

The back end is written in Python utilizing Flask and BS4.
