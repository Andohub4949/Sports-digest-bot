# Sports Digest Telegram Bot

Sends a daily sports news digest (football, F1, golf, snooker, darts, and more) to your Telegram at 06:30 BST.

## Setup

1. Create a Telegram bot using BotFather. Save your bot token.
2. Get your chat ID by sending a message to the bot and visiting:
   https://api.telegram.org/bot<YOUR_BOT_TOKEN>/getUpdates
3. Create a GitHub repo and upload these files.
4. Sign up/log in to Railway.
5. New Project → Deploy from GitHub → select repo.
6. Add environment variables:
   - BOT_TOKEN = your Telegram bot token
   - CHAT_ID = your chat ID
7. Deploy → bot sends daily digest at 06:30 BST.
