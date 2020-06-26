# Weather_app：
## Overview
This is a small full stack project that enables people to acquire current city weather information. This web applicaiton is mainly implemented by Python and Django framework.
[Try it!](https://xuliang-weather-app.herokuapp.com/)

<div align=center> <img src="https://github.com/xuliang2019/weather_app/raw/master/weather/static/weather/img/weather_logo.jpg" width="200"> </div>

## Installation
------------
1. Use `git clone` to download the whole files:
```
git clone https://github.com/xuliang2019/weather-app.git
```
2. Create a virtual environment and activate it inside the project folder:
```
python -m venv my_env
cd my_env
Scripts\activate
```
3. Install the dependencies listed in the `requirements.txt` file under root directory :
```
pip install -r requirements.txt
```
4. Get your own [``Open weather api key``](https://openweathermap.org/api) and add it to the `url` variable under the directory of `weather/views.py`
5. Run your server and try the app at root directory:
```
python manage.py runserver
```
And you will see below interface. Congratulations!
### Note: Do remember to add your own open weather api key to the `url` variable, otherwise you will catch a server error.
## Demo
<div align=center> <img src="https://github.com/xuliang2019/weather_app/raw/master/weather/static/weather/img/weather_static.jpg" width="600"> </div>



