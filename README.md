![Screenshot_1](https://github.com/user-attachments/assets/81c217b6-2758-48e0-ba89-33689e299cbb)

# BlitzGen Telegram Bot

BlitzGen is a powerful and licensed Telegram bot developed by [MrGrassss](https://t.me/MrGrassss) that simplifies and significantly enhances the efficiency of generating and saving multiple Telegram accounts. 
[MrGrassss](https://t.me/MrGrassss) Also owns an allround telegram bot for all your needs.

---

## Features

- **Telethon and Pyrogram Support:** Choose your preferred Telegram API (Telethon or Pyrogram) for account creation.
- **Multi-Number Services:** Supports 5sim, SMS Activate and SMS bower for virtual number acquisition.
- **Emulator Management:** Detect and use available LDPlayer emulators for multi-account creation.
- **Permissions Handling:** Automate the process of granting necessary permissions to the Telegram app.
- **Rate Limit Workaround:** Implements strategies to work around rate limits during account creation.
- **Automatic Number Cancellation:** Automatically cancels purchased numbers when needed to optimize usage.
- **Auto-Retries on Bans:** Provides automatic retries for number purchase on bans, reducing manual intervention.
- **Interactive Menu:** Provides an interactive menu for user-friendly navigation.
- **User Feedback:** Displays real-time feedback on account creation progress.
- **2FA Support:** Reset numbers with a password, email, or SMS-based two-factor authentication (2FA) for account.
- **Secure Accounts:** Option to set two-factor authentication (2FA) to created accounts and remove them whenever.
- **Profile Picture Changer:** Existing images in the profile_pics folder will randomly be selected during account creation.
- **Clean Contact List:** Searches for existing contacts and removes all of them for an account.
- **Username Changer:** The possibility to randomly add usernames during account creation.
- **Change Accounts API:** Login to created accounts and change the accounts to either pyrogram or telethon
- **Kopeechka Mail support:** Retrieve e-mails for receiving verification codes through Kopeechka.

## Prerequisites

- Install [LDPlayer](https://www.ldplayer.net/) 9.
- LDPlayer must be running, and ADB debugging should be set to 'Open local connection' for BlitzGen to function properly.
- To run multiple instances, you can press Ctrl + 2 in LDPlayer to open the instance manager and clone your instance.
- LDPlayer instances should always be in tablet mode with a resolution of 1600x900 (dpi 240).
- Fill in the required information in the `config.json` file. Information on the config can be found below.
- Choose either Telethon or Pyrogram as your Telegram API.

## Configuration

In your `config.json` file, you can configure the following options:

```json
{
  "5sim-token": "",
  "sms-activate-token": "",
  "smsbower-token": "",
  "kopeechka-token": "",
  "operator": "any",
  "telegram_api": "pyrogram",
  "max_wait_time_code": 60,
  "add_two_faq": true,
  "two_faq_pass": "",
  "randomize_username": true,
  "sim_provider": "5sim"
}
