🎬 Movie Recommendation Telegram Bot

A simple Telegram bot built with Python and the pyTelegramBotAPI library (telebot) that recommends movies based on user preferences such as genre, year, actor, and rating.

📌 Features
Select movie preferences using Telegram buttons
Filter movies by:
Genre
Year
Actor
Minimum rating
Shows top 3 movie recommendations
Saves user preferences in data.json
Loads movie database from movies.json

🛠 Technologies Used
Python 3
pyTelegramBotAPI (telebot)
JSON for data storage

📂 Project Structure
project/
│
├── bot.py            # Main bot code
├── movies.json       # Movie database
├── data.json         # Saved user preferences
└── README.md         # Project documentation

⚙️ Installation
1. Clone the repository
git clone https://github.com/yourusername/movie-telegram-bot.git
cd movie-telegram-bot
2. Install dependencies
pip install pyTelegramBotAPI

▶️ Running the Bot

Run the following command:
python bot.py

py
🔑 Telegram Bot Token
Replace this line in the code:\
bot = telebot.TeleBot('YOUR_BOT_TOKEN')
with your own Telegram Bot token from BotFather.

.

📄 movies.json Example
[
    {
        "title": "Inception",
        "genre": "Sci-Fi",
        "year": "2010",
        "actor": ["Leonardo DiCaprio"],
        "rating": 8.8
    }
]
📋 How It Works
User starts the bot using /start
Bot shows a menu with filters
User selects preferences
Preferences are saved
Bot searches movies from movies.json
Top movie recommendations are displayed

🎮 Available Commands
Command	Description
/start	Start the bot

📌 Example Interaction
User: /start
Bot:
Hi! 👋 I'm a movie bot 🎬 Choose from menu.
[Genre] [Year]
[Actor] [Rating]
[End]

🚀 Possible Improvements
Add movie posters
Use a real movie API
Add pagination
Add multilingual support
Deploy on a server
Add inline keyboards
Improve recommendation algorithm

👨‍💻 Author
Created with Python and Telegram Bot API.
