# Ruboty
Ruboty on somewhere.

## Setup
```
$ heroku create
$ heroku config:set \
  REDIS_URL="..." \
  SLACK_ROOM="general" \
  SLACK_PASSWORD="..." \
  SLACK_TEAM="tqhouse" \
  SLACK_USERNAME="ellen" \
  TZ="Asia/Tokyo"
$ git push heroku master
$ heroku scale bot=1
```

## Deploy
```
$ git push heroku master
```

## Request
https://github.com/yoshiori/padomi/fork

## Contact
https://github.com/yoshiori/padomi/issues/new
