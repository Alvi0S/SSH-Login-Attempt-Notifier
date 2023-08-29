# SSH-Login-Attempt-Notifier
This is a Telegram Bot created to message you immediately when someone tries to login in to you're SSH server.

Go to telegram and open BOTFATHER account.
Start the BOTFATHER with command '/newboot' to create a new bot.
Follow his instruction to get the API TOKEN (to put it on the script)

Then we change "YOUR_TELEGRAM_BOT_TOKEN" with the API token from BOTFATHER
and the "YOUR_CHAT_ID" with your telegram id so the BOT can send you message, and that's it

Go to you're SSH server with root privilege and write
sudo ./bash.sh
The script will continuously monitor the SSH log file.
