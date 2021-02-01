Monitors mydealz.de and sends new deal postings via a telegram bot to a telegram user.

Make sure to set the 'bot-token' key and 'recipient' key correctly.

Choose a topic and set 'topic' appropriately. 
A topic is valid if it can be accessed via `mydealz.de/gruppe/TOPIC`.
If you want to monitor all deals, set the URL of the first HttpRequestNode to
`mydealz.de`.

To fix the keys on startup, create a 'mydealz.args' file and define the missing
keys.

To start this workflow, execute `scraper` in the same directory as `mydealz.yf`. 

# Dependencies

* [Unstable nodes](https://github.com/scraperflow/scraper-nodes/releases/tag/unstable-v0.3.0)
* [Dev nodes](https://github.com/scraperflow/scraper-nodes/releases/tag/dev-v0.5.0)

# Flow Graph:
![image](https://user-images.githubusercontent.com/38429047/97875691-10e99c80-1d1b-11eb-8cdf-2b5b936902c2.png)


# Quickstart Docker:

1. Set `bot-token` to your telegram bot token and `recipient` to your recipient ID
2. Make sure you can receive messages from your telegram bot
3. Use `docker-compose up` to start the workflow
