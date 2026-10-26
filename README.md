# Telegram Bot

/start কমান্ডে ওয়েলকাম মেসেজ পাঠায়।

## Render-এ ডিপ্লয়
1. এই ফোল্ডারের ফাইলগুলো GitHub রিপোজিটরিতে আপলোড করুন।
2. Render → New → Web Service → রিপোজিটরি সিলেক্ট করুন।
3. Build Command: `pip install -r requirements.txt`
4. Start Command: `python bot.py`
5. Environment Variables-এ `BOT_TOKEN` = আপনার বট টোকেন দিন।
6. Deploy করুন।

## লোকালি রান
```
pip install -r requirements.txt
export BOT_TOKEN=your_token
python bot.py
```
