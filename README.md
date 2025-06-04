# 🐱 CatBot — Telegram Bot in Java

CatBot is a Telegram bot written in Java using the Telegram Bot API. It can respond to commands, interact with users, and send step-by-step images.

## ✨ Features

- Java implementation using Maven
- Handles user commands
- Sends step-by-step images
- Clean project structure with separated logic
- Easy to adapt for other bots

## 🛠️ Tech Stack

- Java 8+
- Maven
- Telegram Bot API
- Telegram Java SDK (e.g., org.telegram.telegrambots)

## 📁 Project Structure

```
├── TelegramBot/
│   ├── src/main/java/ua/javarush/
│   │   ├── MyFirstTelegramBot.java      # Main bot class
│   │   ├── TelegramBotContent.java      # Content logic
│   │   └── TelegramBotUtils.java        # Utility functions
│   ├── images/                          # Step-by-step illustrations
│   ├── pom.xml                          # Maven configuration
├── README.md                            # Project documentation
```

## 🚀 How to Run

1. **Clone the repository and build the project**:
   ```bash
   mvn clean package
   ```

2. **Run the bot** (make sure to insert your own token):
   ```bash
   java -jar target/TelegramBot.jar
   ```

> The bot requires a Telegram Token. Get one from [@BotFather](https://t.me/BotFather)

## 💡 Skills Demonstrated

- Working with Telegram Bot API
- Designing structured bots
- Using Maven and Java
- Handling user commands and media
- Reading and sending images

## 📚 License

This project is open-source and available under the MIT License.

## 👨‍💻 Author

Made with 🐾 by [Tetiana] — aspiring Java developer.
