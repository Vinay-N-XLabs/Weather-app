## Flask Weather App

A simple web application to display the current weather in various cities, built with Python, Flask, SQLAlchemy, SQLite, HTML, and Bulma.

This project is intended to help familiarize myself with web development with Python and Flask, and is based on this [tutorial](https://www.youtube.com/watch?v=lWA0GgUN8kg).

## Project Status
This project is currently in development. Future updates wil include clickable tiles for time, news, etc.

## Installation and Setup Instructions

Clone this repository. You will need `python`, `virtualenv`, and `virtualenvwrapper-win` installed on your machine.

#### Set up a virtual environment:

`mkvirtualenv FlaskWeatherApp`

#### Installation:

`pip install flask`

`pip install flask_sqlalchemy`

`pip install requests`   
`pip install gunicorn`
#### To Start Server:

`gunicorn -b 0.0.0.0:5000 app:app`  
