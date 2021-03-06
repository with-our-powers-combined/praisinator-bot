Praisinator Bot
=========
Praisinator Bot is a Slackbot integration that listens in to your team's public conversations and runs sentiment analysis in real time to report the mood and morale of your team.

It integrates with [Praisinator Web](https://github.com/praisinator/praisinator-web) in order to deliver informative analytics and reporting. This allows you to see who's having the most positive and negative effect on your team and take actionable steps to correct or praise them.

Pre-requisites
---------------
- [Have a functioning development environment](http://tutorials.jumpstartlab.com/topics/environment/environment.html)
- Have Node and NPM installed

Installation
--------------
Clone the repo and install its dependencies:
```sh
$ git clone git@github.com:praisinator/praisinator-bot.git
$ cd praisinator-bot/
$ npm install
```

Create a .env file:
```sh
$ touch .env
```

Add the following key/values to said .env:

```
SLACK_CLIENT_ID=9094370912.22344990885
SLACK_CLIENT_SECRET=[SLACK_CLIENT_SECRET_HERE]
PRAISINATOR_URI=praisinator-bot.herokuapp.com
PRAISINATOR_API=http://praisinator-web.herokuapp.com/api/
```

Run the Server
---------------
Just type:
```sh
$ node app/server.js
```
and visit [praisinator-bot.herokuapp.com](praisinator-bot.herokuapp.com).
