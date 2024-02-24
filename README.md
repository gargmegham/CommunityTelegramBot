# Crypto Community Telegram Bot

This repository contains the source code for a Telegram bot developed using the Telegram Bot API and the python-telegram-bot library.

## Description

The Telegram bot implemented in this project is designed to perform various tasks within Telegram chats and groups. It includes features such as:

- Tracking chat membership changes
- Greeting new members and handling member departures
- Managing chat memberships and interactions
- Handling errors and logging

## Features

- **Track Chats**: The bot tracks changes in chat membership and logs events such as adding or removing the bot from chats.

- **Greet Chat Members**: The bot welcomes new members to chats and takes action based on user interactions.

- **Error Handling**: Error handling is implemented to log exceptions and notify developers about issues encountered during bot operation.

## Usage

To use the bot, you need to create a `secrets.json` file containing the bot's API token and other sensitive information. The file should be structured as follows:

```json
{
  "secrets": {
    "BOT_API_TOKEN": "YOUR_BOT_API_TOKEN",
    "DEV_USER": "YOUR_TELEGRAM_USER_ID",
    "CHAT_HANDLE": "YOUR_TELEGRAM_CHAT_HANDLE"
  }
}
```

Replace "YOUR_BOT_API_TOKEN", "YOUR_TELEGRAM_USER_ID", and "YOUR_TELEGRAM_CHAT_HANDLE" with your actual bot API token, your Telegram user ID for receiving error notifications, and your Telegram chat handle, respectively.

## Installation

- Clone the repository:

```bash
Copy code
git clone https://github.com/gargmegham/CommunityTelegramBot.git
cd CommunityTelegramBot
pip install -r requirements.txt
python bot.py
```

## Contributing

Contributions to this repository are welcome! If you have suggestions for improvements or new features, feel free to open an issue or submit a pull request & use [contribution guidelines](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).
You can customize this README according to your specific project details and requirements.
