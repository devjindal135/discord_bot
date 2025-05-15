# Discord Bot

A Discord bot built with Python.

## Features

- [List your bot's features here]

## Installation

1. Clone the repository
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Configure your environment variables (see Configuration section)
4. Run the bot:
   ```
   python bot.py
   ```

## Setting Up Your Discord Bot

1. Go to the [Discord Developer Portal](https://discord.com/developers/applications)
2. Click on "New Application" and give your bot a name
3. Navigate to the "Bot" tab and click "Add Bot"
4. Under the Token section, click "Copy" to copy your bot's token (you'll need this for the `.env` file)
5. Scroll down to "Privileged Gateway Intents" and enable:
   - Presence Intent
   - Server Members Intent
   - Message Content Intent
6. Go to the "OAuth2" tab, select "URL Generator"
7. Under "Scopes" select "bot" and "applications.commands"
8. Under "Bot Permissions" select the permissions your bot needs (common ones include "Send Messages", "Read Message History", "Manage Messages")
9. Copy the generated URL and paste it in your browser to invite the bot to your server

## Configuration

Create a `.env` file in the root directory with the following variables:

```
API_KEY=your_discord_token
```

## Commands

- $meme