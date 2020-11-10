# Weight Converter Intro App : Using Flask, Python, Heroku

## Heroku Setup:
- Install gunicorn for creating requirements file for Heroku
```buildoutcfg
> pip install gunicorn
> pip freeze > requirements.txt
```
- Create Heroku account : https://signup.heroku.com/
- Download & Install Heroku CLI: https://devcenter.heroku.com/articles/heroku-cli#download-and-install
- Create New Heroku App and Push to deploy:
```buildoutcfg
> heroku create flask-app
> git push heroku master
```
https://honeyb-flask-app.herokuapp.com/
