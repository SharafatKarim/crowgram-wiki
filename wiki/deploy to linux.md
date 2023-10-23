## Prerequisites

Before you begin, please make sure you have the following variables ready:

- `api_id`: Your Telegram API ID.
- `api_hash`: Your Telegram API hash.
- `string`: A session string for your bot.
- `bot_token`: Your Telegram bot token.
- `assistant_bot`: The username of your assistant bot.
- `assistant_api_id`: API ID for your assistant bot.
- `assistant_api_hash`: API hash for your assistant bot.
- `assistant_string`: A session string for your assistant bot.
- `owner`: Your Telegram user ID.
- `log_group`: The ID of the log group for your bot.
- `pm_log_location`: Location for private message logs.
- `mention_log_location`: Location for mention logs.

## Installation Steps

Follow these steps to install Crowgram on your Linux machine.

### Automatic Process

The easiest and our recommended process to install Crowgram is to run the following command in your linux terminal in your desired directory.
```bash
curl -s https://raw.githubusercontent.com/iniridwanul/Crowgram/master/crowgram.sh > install.sh && bash install.sh && rm install.sh
```

It'll automatically clone the git repository, and will ask you for your variables and do the rest. Here the only dependences for running this command are `wget`, `git` and your Linux shell itself!

For again running the bot, simply run the `crowgram.sh` script inside the git repository.
```bash
bash crowgram.sh
```

### Manual Process
1. **Clone the Crowgram Repository**

   Open your terminal and run the following command to clone the Crowgram repository:

   ```bash
   git clone https://github.com/your_username/crowgram.git
   ```

2. **Navigate to the Crowgram Directory**

   Change your current directory to the Crowgram folder:

   ```bash
   cd crowgram
   ```

3. **Set Environment Variables**

   Export the environment variables using the values you gathered in the prerequisites step. You can set them in the `.env` file provided with the repository:

   ```bash
   echo "api_id=YOUR_API_ID" >> .env
   echo "api_hash=YOUR_API_HASH" >> .env
   echo "string=YOUR_SESSION_STRING" >> .env
   echo "bot_token=YOUR_BOT_TOKEN" >> .env
   echo "assistant_bot=YOUR_ASSISTANT_BOT" >> .env
   echo "assistant_api_id=ASSISTANT_API_ID" >> .env
   echo "assistant_api_hash=ASSISTANT_API_HASH" >> .env
   echo "assistant_string=ASSISTANT_SESSION_STRING" >> .env
   echo "owner=YOUR_TELEGRAM_USER_ID" >> .env
   echo "log_group=YOUR_LOG_GROUP_ID" >> .env
   echo "pm_log_location=YOUR_PM_LOG_LOCATION" >> .env
   echo "mention_log_location=YOUR_MENTION_LOG_LOCATION" >> .env
   ```

   Replace `YOUR_XXX` with the respective values.

4. **Install Dependencies and start Crowgram**

   Run the following command to install the required dependencies and start your own crowgram:

   ```bash
   bash crowgram.sh
   ```

   Crowgram will initialize and connect to Telegram.

## Usage

Crowgram is now up and running on your Linux machine. You can interact with it using your Telegram account. Refer to the [Crowgram documentation](https://crowgram.gitbook.io/crowgram/) for information on available commands and features.

## Conclusion

You have successfully installed Crowgram on your Linux machine. Enjoy the enhanced Telegram experience provided by this userbot!

If you encounter any issues or have questions, please refer to the [Crowgram GitHub repository](https://github.com/iniridwanul/Crowgram) or reach out to the developer community for assistance.