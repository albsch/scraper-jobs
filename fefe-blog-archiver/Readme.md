Monitors blog.fefe.de and sends new blog postings via a telegram bot to a telegram user.

Does not crash or resend a blog post on failure to send a telegram message.

Make sure to set the 'bot-token' key and 'recipient' key correctly.

To fix the keys on startup, create a 'fefe.args' file and define these two keys there:

```
bot-token=...
recipient=...
```

To start this workflow, execute `scraper` in the same directory as `fefe.yf`. 
If it is not the only `yf` file, execute `scraper fefe.yf`instead.

# Dependencies

* [Unstable nodes](https://github.com/scraperflow/scraper-nodes/releases/tag/unstable-v0.1.0)
* [Dev nodes](https://github.com/scraperflow/scraper-nodes/releases/tag/dev-v0.2.2)

# Flow Graph:
![image](https://user-images.githubusercontent.com/38429047/76775323-7b0dfb00-67a5-11ea-8e37-438211fc7234.png)
