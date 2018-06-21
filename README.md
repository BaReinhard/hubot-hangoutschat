# hubot-hangoutschat-public

The Hangouts Chat provider for Github's Hubot

## How to use

Make sure to set the GOOGLE_APPLICATION_CREDENTIALS environment variable pointing to the JSON file that you received for the Google Service Account.

```
export GOOGLE_APPLICATION_CREDENTIALS="/path/to/credentials.json"
./bin/hubot -a hangoutschat
```

Changes:
Fixes threadding for responses as well as handles using the bot in rooms.

Hangouts Chat Bot Name should be the same name as located in your `bin/hubot` script.
