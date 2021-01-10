## About Me

Python Backend Software Developer looking for Junior/Middle-level positions.  
__`Python` `Django` `Django REST` `Flask` `SQL` `Git` `Linux` `Docker` `AWS`__  

## Pet Projects

### Blogging social network: [ThePost](https://github.com/Arseniy-Popov/ThePost)
__`Python` `Django` `PostgreSQL` `pytest` `Docker` `docker-compose` `AWS EC2` `gunicorn` `nginx`__
- Generic social network with users, posts, comments on posts, subscribing to users, and feeds of posts of followed users.
- Built with `Python`, `Django`, and `PostgreSQL`; tested with `pytest`.
- Deployed to [thepost.arseniypopov.com](http://thepost.arseniypopov.com/) with `AWS EC2`, `gunicorn`, and `nginx`; containerized with `Docker` and `docker-compose`.

### Ratings database API: [RatingDB](https://github.com/Arseniy-Popov/RatingDB)  
__`Python` `Django` `Django REST` `PostgreSQL` `pytest` `Docker` `docker-compose` `AWS EC2` `gunicorn` `nginx`__
- API for a database of titles (characterised by categories and genres), users with roles and permissions, reviews on and ratings of titles, and comments on reviews. Documented at [redoc](http://api.rating-db.arseniypopov.com/docs/redoc.html) / [swagger](http://api.rating-db.arseniypopov.com/docs/swagger.html).
- Built with `Python`, `Django REST Framework`, and `PostgreSQL`; tested with `pytest`.
- Deployed to [api.rating-db.arseniypopov.com](http://api.rating-db.arseniypopov.com/api/v1/) with `AWS EC2`, `gunicorn`, and `nginx`; containerized with `Docker` and `docker-compose`.

### Backend API powering a weather forecast Telegram bot: [TodayWeatherBot](https://github.com/Arseniy-Popov/TodayWeatherBot)
__`Python` `Flask` `PostgreSQL` `SQLAlchemy` `pytest` `unittest` `Google Geocoding API` `OpenWeatherMap API` `Docker` `docker-compose` `AWS EC2` `Heroku` `marshmallow` `python-telegram-bot` `pyrogram` `gunicorn` `nginx`__
* The backend API is at [api.today-weather.arseniypopov.com](http://api.today-weather.arseniypopov.com), is documented at [redoc](http://api.today-weather.arseniypopov.com/docs/redoc.html) / [swagger](http://api.today-weather.arseniypopov.com/docs/swagger.html), and returns a weather forecast for the remainder of the current day in response to a free form address input. The telegram bot, at [TodayWeatherBot](https://t.me/AMP_TodayWeatherBot), feeds off the backend API.
* Built with `Flask` as a web framework and `marshmallow` for object serialization; utilizes `Google Geocoding API` to interpret free-form address input and `OpenWeatherMap API` to obtain weather forecasts; uses `PostgreSQL` for storing localities and caching the mapping from free-form address inputs to localities with `SQLAlchemy` as an ORM; tested with `pytest`; deployed to `AWS EC2` with `nginx` and `gunicorn`; containerized with `Docker` and `docker-compose`.
* The bot is deployed to `Heroku`; built with `python-telegram-bot` as a wrapper around Telegram's API; uses `PostgreSQL` and `SQLAlchemy` for storing user's latest and default addresses; tested with `unittest`.



