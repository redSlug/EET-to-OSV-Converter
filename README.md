# EET to OSV Converter
[Grammar in ASL](http://www.lifeprint.com/asl101/pages-layout/grammar.htm) is not the same as spoken English. For example, 'to be' verbs do not exist, there are many different arragements of parts of speech, and adjectives tend to go after nouns. 

This is a tool people learning ASL, who wish to switch from an Exact English Translation to an expression resembling topicalized Object Subject Verb order.

## Setup
- clone and cd into repo
- `pip install -r requirements.txt`
- run locally `python main.py`

## Deploy
- create a heroku account and app
- `heroku login`
- `heroku git:remote -a <app name>`
- `git push heroku master`

![picture of app](img.png)

