PAREI Receiving Form Data

# Exploring Riot Games API

This [API](https://developer.riotgames.com/)  provides access for all information about the game, matches, players, etc. The objective of this project
is to learn about the API and in the future to develop a system to provide insights to players to improve their game play.
For a while, this project will show this way.



### Requirements

- [Flask](http://flask.pocoo.org/)
- [Flask-WTF](https://pythonhosted.org/Flask-WTF/)

### Installation


``` console

$ conda info --envs
$ conda create --name lol_flask
$ conda activate lol_flask
$ pip install -r requirements.txt
```


### Execute Webpage
It's necessary to activate the lol_flask enviroment.

- For windows 
``` console
$ set FLASK_APP=blog.py
$ set FLASK_DEBUG=1 *(optional)
$ flask run
```

- For others OS 
``` console
$ export FLASK_APP=blog.py
$ export FLASK_DEBUG=1 *(optional)
$ flask run
```



