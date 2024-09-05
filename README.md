# IMDb Movie Information Telegram Bot

A Telegram bot built with Python to fetch and display movie details from IMDb using the OMDB API. It allows users to interact by entering movie titles and provides information such as ratings, release dates, and cast details. The bot can also export the fetched data in CSV format through Telegram.

## Features
- Fetch movie details using the OMDB API.
- Provide instant movie info via Telegram commands.
- Export movie data to CSV format and send via Telegram.

## Tech Stack
- **Python** for the bot and backend logic.
- **Telebot** for Telegram bot functionality.
- **Requests** for API calls to OMDB.
- **CSV** for data export.
- **OMDB API** for movie data.

## Bot Commands
- `/start` or `/hello` - Start the bot.
- `/movie MOVIE_NAME` - Get information on a specific movie.
- `/export` - Export movie data to a CSV file.
- `/stop` or `/bye` - Stop the bot and clean up.

## Challenges Faced
- Managing API responses with varied movie titles.
- Ensuring smooth interaction between the Telegram bot and the OMDB API.
- Handling CSV file creation and sending through Telegram.
