Telegram bot with a weather forecast for the day: [TodayWeatherBot](https://github.com/Arseniy-Popov/TodayWeatherBot)  
`Python` `PostgreSQL` `Google Geocoding API` `OpenWeatherMap API` `Heroku` `SQLAlchemy` `unittest` `python-telegram-bot` `pyrogram`
* deployed to `Heroku` at [TodayWeatherBot](https://t.me/AMP_TodayWeatherBot)
* built with `python-telegram-bot` as a wrapper around Telegram's API
* utilizes `Google Geocoding API` to interpret free-form address input and `OpenWeatherMap API` to obtain weather forecasts
* uses `PostgreSQL` for storing user data like the default/latest addresses and for caching the mapping from free-form
address inputs to geographic localities
* employs `SQLAlchemy` as an ORM
* applies `unittest` as a testing framework and `pyrogram` as Telegram API wrapper for integration testing allowing
to test both the development version (with database and client resets between tests) and the deployed version     
   
   
A blogging platform: [ThePost](https://github.com/Arseniy-Popov/ThePost)  
`Python` `Django` `Django REST Framework` `PostgreSQL`
* Built with `Django`, `Django REST Framework`, `Bootstrap`, and `PostgreSQL`
* ~~Deployed to [thepost.arseniypopov.com](https://thepost.arseniypopov.com/) via `AWS EC2` with `nginx` and `gunicorn`~~
