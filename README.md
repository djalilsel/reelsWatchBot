# reelsWatchBot

## Description
reelsWatchBot is a Python package that allows you to create a Telegram bot that can download Instagram Reels from any public Instagram page. The bot uses the Instapy package to download the reels from the links sent by the users. The bot can be customized to handle different types of messages and commands, and can be deployed on any platform that supports Python. The package is easy to use and can be customized to suit your needs.

## Features

- **Token-Based Initialization**: Start the bot using a user-provided Telegram bot token.
- **Instagram Reels Link Listener**: Automatically listen for Instagram reels links shared by users in the chat.
- **File Downloading**: Download shared Instagram reels links directly to local storage.
- **User Notifications**: Notify users upon successful download of the reels.
- **Error Handling**: Gracefully handle errors related to invalid links or download failures.
- **Custom Command Support**: Allow users to interact with the bot using custom commands.
- **Flexible Integration**: Easily integrate the bot into existing Python projects and customize its behavior.

## Installation

```bash
pip install reelsWatchBot
```
## Example

Make sure to replace the placeholders with the correct values:

```python
from reelsWatchBot import ReelsWatchBot

TELEGRAM_BOT_TOKEN = 'token' # Replace with your bots token
VIDEOS_PATH = 'path/to/save/videos' # Replace with the path where you want the videos to be saved

# Initialize bot with bot token
bot = ReelsWatchBot(TELEGRAM_BOT_TOKEN, path=VIDEOS_PATH)
# Run the bot
bot.run_bot()
```
