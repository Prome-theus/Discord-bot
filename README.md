# Discord Welcome Bot in Python

<div align="center">
  <img src="https://github.com/Prome-theus/Discord-bot/assets/80052733/7bd6e00a-e476-44ce-84a8-73e45b9ec415" alt="Discord Welcome Bot">
</div>



Welcome to the Discord Welcome Bot repository! This Python bot is designed to enhance your Discord server by providing a warm welcome to new members. The bot sends a personalized welcome message to users as they join your server, creating a friendly and inviting atmosphere.

## Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your-username/discord-welcome-bot.git
   ```

2. **Install Dependencies:**

   Navigate to the project directory and install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. **Configure the Bot:**

   Copy the `config.example.json` file and rename it to `config.json`. Open the `config.json` file and add your Discord bot token and set other configuration options as needed.

4. **Run the Bot:**

   Run the bot script:

   ```bash
   python bot.py
   ```

   Ensure that your Discord bot is invited to your server and has the necessary permissions.

## Configuration

Customize the bot's behavior by modifying the options in the `config.json` file. You can adjust the welcome message, specify the channel where the welcome message should be sent, and more.

```json
{
  "token": "YOUR_DISCORD_BOT_TOKEN",
  "prefix": "!",
  "welcome_channel_id": "YOUR_WELCOME_CHANNEL_ID",
  "welcome_message": "Welcome to the server, {user_tag}! We're glad to have you here.",
  "enable_private_message": true
}
```

---
