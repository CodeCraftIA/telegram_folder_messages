# telegram_folder_messages
Sent message to all the chats in telegram under a specific folder

This script uses Telethon to find all chats in a specific folder (named "spam" by default) and sends a predefined message to all of them. You can change the folder name to your desired.

# Update API Credentials
Replace api_id and api_hash with your Telegram API credentials. Obtain these credentials by creating a new application at Telegram's development platform.

# Specify the Message and Folder Name
Replace the message variable with the message you want to send.
Update the folder name in the script if you want to target a folder other than "spam".

# Usage
The script performs the following steps: it retrieves all chats in a specified folder and sends a fixed message to each chat.
