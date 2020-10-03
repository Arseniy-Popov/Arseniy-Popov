## About Me

Python Backend Software Developer looking for Junior/Middle-level positions.  
__`Python` `Django` `Django REST Framework` `Flask` `SQL` `Git` `Linux` `REST API` `Docker` `docker-compose` `AWS` `pytest`__

## Pet Projects

### 1. Backend API powering a Telegram bot with a weather forecast for the day: [TodayWeatherBot](https://github.com/Arseniy-Popov/TodayWeatherBot)
__`Python` `Flask` `PostgreSQL` `SQLAlchemy` `pytest` `unittest` `Google Geocoding API` `OpenWeatherMap API` `Docker` `docker-compose` `AWS EC2` `Heroku` `marshmallow` `python-telegram-bot` `pyrogram` `gunicorn` `nginx`__
###### About
* backend API powering a Telegram bot with a weather forecast for the day
* returns a weather forecast for the remainder of the current day in response to a free form address input
* the backend API, at [api.today-weather.arseniypopov.com](http://api.today-weather.arseniypopov.com), is documented in [redoc](http://api.today-weather.arseniypopov.com/docs/redoc.html) and [swagger](http://api.today-weather.arseniypopov.com/docs/swagger.html) (interactive) formats
* following a POST request to /localities with a free form address input, the server checks if "москва" maps to any of the saved localities. If not, it sends a request to geocode "москва" to Google Geocoding API and maps "москва" to the received locality. The coordinates of the locality, cached or obtained from Google Geocoding API, are sent to OpenWeatherMap API to obtain a weather forecast. It is then processed and returned to the user, together with a reference, /localities/{id}, to the locality
* the telegram bot, at [TodayWeatherBot](https://t.me/AMP_TodayWeatherBot), feeds off the backend API, and supports free form address input, setting a default locality, and requesting forecasts for latest and default localities
###### Built with
* built with `Flask` as a web framework and `marshmallow` for object serialization 
* utilizes `Google Geocoding API` to interpret free-form address input and `OpenWeatherMap API` to obtain weather forecasts
* uses `PostgreSQL` for storing localities and caching the mapping from free-form address inputs to localities with `SQLAlchemy` as an ORM
* tested with `pytest`
* deployed to `AWS EC2` with `nginx` and `gunicorn`; containerized with `Docker` and `docker-compose`
* the telegram bot is deployed to `Heroku`; built with `python-telegram-bot` as a wrapper around Telegram's API; uses `PostgreSQL` and `SQLAlchemy` for storing user's latest and default addresses; tested with `unittest`

### 2. A blogging platform: [ThePost](https://github.com/Arseniy-Popov/ThePost)
__`Python` `Django` `Django REST Framework` `PostgreSQL`__
* Built with `Django`, `Django REST Framework`, `Bootstrap`, and `PostgreSQL`
* ~~Deployed to [thepost.arseniypopov.com](https://thepost.arseniypopov.com/) via `AWS EC2` with `nginx` and `gunicorn`~~
