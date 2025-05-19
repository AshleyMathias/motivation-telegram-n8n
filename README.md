Daily Motivational Quotes Telegram Bot

This project is an automated Telegram bot built using n8n workflow automation. It sends a daily motivational quote to a specified Telegram chat, helping users start their day with inspiration.

Features

Automated daily trigger at a specified time.  
Fetches a random motivational quote from a free public API (Quotable).  
Sends the quote as a message directly to a Telegram chat using a Telegram bot.  
Simple, no-code/low-code workflow built entirely in n8n.

Technologies Used

n8n — Workflow automation tool  
Telegram Bot API — For sending messages  
Quotable API — Free public quotes API

How It Works

First, a Cron Node triggers the workflow once every day at a configured time.  
Next, the HTTP Request Node fetches a random quote from the Quotable API.  
Finally, the Telegram Node sends the quote text as a message to the configured Telegram chat.

Setup Instructions

Create a Telegram Bot by talking to [@BotFather](https://t.me/BotFather) on Telegram to get its token.

Get your Telegram Chat ID by using [@userinfobot](https://t.me/userinfobot) or by setting up a Telegram Trigger node in n8n to capture it.

Configure the n8n workflow by importing or creating the three nodes: Cron, HTTP Request, and Telegram. Set your Telegram Bot Token and Chat ID in the Telegram node. Set the HTTP Request node URL to `https://api.quotable.io/random`.

Run and test the workflow manually or wait for the daily trigger to see the message on Telegram.

Usage

Once set up, the bot will automatically send a motivational quote every day to your Telegram chat at the scheduled time. No further action is needed.

epository

You can find the workflow file and related configuration in this repository.

Contact

Feel free to connect with me or check out my projects here:

LinkedIn: [linkedin.com/in/ashleymathia10](https://www.linkedin.com/in/ashleymathia10)  
GitHub: [github.com/AshleyMathias](https://github.com/AshleyMathias)
