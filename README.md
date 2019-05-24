[![CircleCI](https://circleci.com/gh/dashwav/nano-chan/tree/master.svg?style=svg)](https://circleci.com/gh/dashwav/nano-chan/tree/master)
# nano-chan
(Not so) General purpose discord bot written in python for the discord.py rewrite library

I try to code this in a style that will continually surprise me no matter how often I look at the codebase

Requirements:
```
Docker (CE edition is fine)
```

Steps to run:

* Clone repo (duh)
* Copy config/example_config.yml to config/config.yml and edit values as needed.
* Run `docker-compose up`
* Invite bot to server.

Once you have changed some code:

* Run `docker-compose build yinbot`
* Re-run `docker-compose up`

## Common Issues:
