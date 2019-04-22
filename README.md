This real estate company website features realtors and their listings. 

Tools:
Python
Django
postgreSQL
Heroku

Demo: https://djangorealestateapp.herokuapp.com/ 

To do: Use S3 with Heroku to have uploaded images for listings to persist in the postgreSQL database with Heroku. 

![Imgur](https://i.imgur.com/sTwzdcj.png) 

To Run Locally:

Activate the virtual environment source venv/bin/activate
install requirements.txt  pip install -r requirements.txt
python manage.py migration
python manage.py runserver
