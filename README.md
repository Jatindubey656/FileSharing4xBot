[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy)


### Admin Commands

```
/start - start the bot or get posts
/batch - create link for more than one posts
/genlink - create link for one post
/users - view bot statistics
/broadcast - broadcast any messages to bot users
```
### Variables

* `API_HASH` Your API Hash from my.telegram.org
* `API_ID` Your API ID from my.telegram.org
* `TG_BOT_TOKEN` Your bot token from @BotFather
* `OWNER_ID` Must enter Your Telegram Id
* `CHANNEL_ID` Your Channel ID eg:- -100xxxxxxxx
* `CUSTOM_CAPTION` put your Custom caption text if you want Setup Custom Caption
* `ADMINS` Optional: A space separated list of user_ids of Admins, they can only create links
* `FORCE_SUB_CHANNEL` Optional: ForceSub Channel ID, leave 0 if you want disable force sub


#### Deploy in your VPS
````bash
$ git clone https://github.com/DollyBots/FileSharing4xBot
$ cd FileSharing4xBot
$ pip3 install -r requirements.txt
$ python3 main.py
````


##

   **Star this Repo if you Liked it ⭐⭐⭐ | @DollyBots**