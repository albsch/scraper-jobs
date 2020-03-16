Monitors blog.fefe.de and sends new blog postings via a telegram bot to a telegram user.

Does not crash or resend a blog post on failure to send a telegram message.

Make sure to set the 'bot-token' key and 'recipient' key correctly.

To fix the keys on startup, create a 'fefe.args' file and define these two keys there:

```
bot-token=...
recipient=...
```

# Flow Graph:
![image](https://user-images.githubusercontent.com/38429047/76775323-7b0dfb00-67a5-11ea-8e37-438211fc7234.png)
