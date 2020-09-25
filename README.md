# Fake News Detector

**An actual real life application to check the news you get .** 

## What makes it one of a kind!

  - ##### A actual real life news checker anytime,anywhere.
  - ##### Complete privacy , messages checked by machine learning no actual human would read your message
  - ##### Available on two platforms, Whatsapp/Telegram ,soon more to come.
## Wanna try it for yourself ?
The user need to save the official twilio number i.e(+1 415 523 8886)  after saving this number they need to send a code this number for this project it is "join wet-forgot" .To redirect their messages to our servers hosted on heroku .(https://thawing-springs-11284.herokuapp.com/) .
After this is done now the user just needs to forward /share any news they receive on whatsapp and
they will get a message , telling them whether their news is real or fake .


### Tech Stack:-

Our Detector  uses a number of framework to work properly:

* ##### Flask 
* ##### Jsonify
* ##### NLTK
* ##### Tensorflow
* ##### Pandas
* ##### Pickle
* ##### Numpy
* ##### Regex

### Wanna See for yourself how it runs? 

**Fake news Detector requires Tensorflow v2+ to run.**

Install the dependencies  using ``` $ pip install -r requirements.txt ```

```sh
$ cd Fakenews
$ python3 flask_server.py 
```

* Also if you wanna retrain the model it is super simple take few news item and use the train_model fuction in model.py
* You can save the incoming messages as well

### How it looks 
we know it looks simple but that was intentional :)
![screenshot of whatsapp ](https://github.com/KartikKapil/Fakenews/blob/master/Screenshot%20from%202020-09-25%2018-28-08.png)
