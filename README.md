## Variables

### Required Variables

* `BOT_TOKEN`: Create a bot using [@BotFather](https://telegram.dog/BotFather), and get the Telegram API token.
* `API_ID`: Get this value from [telegram.org](https://my.telegram.org/apps)
* `API_HASH`: Get this value from [telegram.org](https://my.telegram.org/apps)
* `CHANNELS`: Username or ID of channel or group. Separate multiple IDs by space
* `ADMINS`: Username or ID of Admin. Separate multiple Admins by space
* `DATABASE_URI`: [mongoDB](https://www.mongodb.com) URI
* `DATABASE_NAME`: Name of the database in [mongoDB](https://www.mongodb.com)
* `LOG_CHANNEL`: A channel to log the activities of bot. Make sure bot is an admin in the channel.

### Optional Variables

* `COLLECTION_NAME`: Name of the collections. Defaults to Telegram_files. If you are using the same database, then use different collection name for each bot
* `AUTH_USERS`: Username or ID of users to give access of inline search. Separate multiple users by space.\nLeave it empty if you don't want to restrict bot usage.
* `AUTH_CHANNEL`: ID of channel.Make sure bot is admin in this channel. Without subscribing this channel users cannot use bot.
* `PICS`: Add some telegraph link of pictures .

## Deploy on Railway

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template/rB_BFq)

## Deploy to Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/HansakaAnuhas/EvaMaria)

## Deploy to VPS

```
Edit info.py with variables as given below then run bot.

git clone https://github.com/EvamariaTG/evamaria
# Install Packages
pip3 install -U -r requirements.txt
python3 bot.py
```
