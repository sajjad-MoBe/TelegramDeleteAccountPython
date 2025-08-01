# 🗑️ Telegram Delete Account Bot (Python)

A simple Telegram bot that helps users **delete their Telegram accounts** through telegram bot.

## 🚀 Features

* Built with **Python + Telethon**
* Accepts user's **phone number** and **verification code**
* Handles the full flow to **delete the Telegram account**
* Easy to run with your own bot token

## 🧹 Requirements

* Python 3.7+
* `telethon` library
  Install with:

  ```bash
  pip install telethon
  ```

## ⚙️ Configuration

Edit the following lines in the script to use your own Telegram API credentials:

```python
#################################
api_id = '1234123' #your api_id
api_hash = 'Sajjad Mobe' #your api_hash
bot_token = '2003:imSajjadMB' #your bot token
#################################
```

You can get your `api_id` and `api_hash` from [my.telegram.org](https://my.telegram.org).

> ⚠️ **Do not share your credentials publicly.**

## 🧠 How It Works

1. Run the bot:

   ```bash
   python bot.py
   ```
2. Open Telegram and message the bot.
3. Send your **phone number** (with country code).
4. Enter the **verification code** when prompted.
5. The bot will handle the deletion process via the Telegram API.

## 📌 Notes

* Account deletion is **irreversible**. Use carefully.
* Make sure the number you send is linked to a real Telegram account.

## 👤 Author

Coded with ❤️ by **Sajjad Mo-Be**
📬 Telegram: [@imSajjadMB](https://t.me/imSajjadMB)
