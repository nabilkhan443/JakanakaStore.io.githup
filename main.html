import telebot
import requests
from telebot import types
#for more join @JakanakaStore & @JakanakaStore
# Your bot token
API_TOKEN = '7940424789:AAG1NzKI_OxH3zVW0GZa2hN5JQrKRlun2Eo'
CHANNEL_USERNAME = '@JakanakaStore'  # Replace with your channel username
bot = telebot.TeleBot(API_TOKEN)

def is_user_member(chat_id):
    try:
        member = bot.get_chat_member(CHANNEL_USERNAME, chat_id)
        return member.status in ['member', 'administrator', 'creator']
    except Exception as e:
        print(e)
        return False

@bot.message_handler(commands=['start'])
def start_command(message):
    if is_user_member(message.chat.id):
                bot.send_message(message.chat.id, "𝗪𝗘𝗟𝗖𝗢𝗠𝗘 𝗧𝗢 JakanakaStore 𝘄𝗲𝗯𝘀𝗶𝘁𝗲 𝗰𝗹𝗼𝗻𝗲𝗿 𝗕𝗢𝗧 𝗜'𝗺 𝗰𝗹𝗼𝗻𝗲 𝗮𝗻𝘆 𝘄𝗲𝗯𝘀𝗶𝘁𝗲 𝘀𝗼𝘂𝗿𝗰𝗲 𝗰𝗼𝗱𝗲       𝗦𝗘𝗡𝗗 𝗠𝗘 𝗔𝗡𝗬 𝗪𝗘𝗕𝗦𝗜𝗧𝗘 𝗟𝗜𝗡𝗞       𝗣𝗼𝘄𝗲𝗿𝗲𝗱 𝗯𝘆 @JakanakaStore")
    else:
        bot.send_message(message.chat.id, f"Please join {CHANNEL_USERNAME} to use this bot.")

@bot.message_handler(func=lambda message: True)
def fetch_website_html(message):
    if not is_user_member(message.chat.id):
        bot.send_message(message.chat.id, f"Please join {CHANNEL_USERNAME} to use this bot.")
        return

    url = message.text.strip()
    bot.send_message(message.chat.id, "Sᴄʀᴀᴘɪɴɢ sᴏᴜʀᴄᴇ ᴄᴏᴅᴇ...")

    try:
        response = requests.get(url, stream=True)
        response.raise_for_status()  # Raise an error for bad responses
        html_content = response.text

        
        file_name = 'JakanakaStorewebsite.html'
        with open(file_name, 'w', encoding='utf-8') as file:
            file.write(html_content)

        with open(file_name, 'rb') as file:
            bot.send_document(message.chat.id, file, caption="Yᴏᴜʀ ᴡᴇʙsɪᴛᴇ sᴏᴜʀᴄᴇ ᴄᴏᴅᴇ sᴜᴄᴄᴇssғᴜʟʟʏ Fᴀᴛᴄʜ ʙʏ @JakanakaStorewebsite_bot.")
            
    except requests.RequestException as e:
        bot.send_message(message.chat.id, f"Error fetching the website: {e}")

if __name__ == '__main__':
    bot.polling(none_stop=True)
    # for more @JakanakaStore