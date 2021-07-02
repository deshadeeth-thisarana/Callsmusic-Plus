# Shadow Music

### ![Shadow](https://telegra.ph/file/66822dc08454b021fd2cf.png)


**A [Shadow Music](https://github.com/deshadeeth-thisarana/shadowmusic) Based Telegram Bot and Userbot To Play Music in Your Telegram Groups With Some Cool Extra Features!**


## Note!⚠️ ,
_**You need another (dummy) Telegram Account To Use/Deploy This!**_

## Features 🔥️

- **Play Music In Telegram Group Voice Chats!** (Supports Multiple Groups)
- **Supports Queues!**
- **Search For YouTube Videos Inline!**
- **Download Yt Songs By It's Name!**
- **Download Yt Videos By It's Name!**
- **Saavn Music Download**
- **Deezer Music Download**
- **Get Voice Chat Link!** (Public Groups Only )
- **Get Lyrics Of Your Song!**
- **Join & Leave Streamer Account Using A Command**
- **Ban / Unban Users and Check User Status.**
- **Broadcast Messages**
- **Quote Messages Like Quotely Bot!**
- **Delete Command Feature**
- **Update Your Bot Without Leaving Telegram**

**Please Refer [Command Explanation](Docs/README.md) to Know How To Use These Commands and Know More About Them!**

## To-Do

- [ ] Add Control by Buttons Feature
- [ ] Remove unnecessary codes to avoid spam in Log Channel
- [ ] Add Thumbnail Generate Support
- [ ] Remove Some unnecessary imports
- [x] ~Fix Youtube Video Downloader~ (Done)
- [x] ~Add Command Delete Feature~ (Done)
- [x] ~Add Quoately Module~ (Done)
- [x] ~Redesign Menu UI~ (Done)
- [x] ~Add Database To Ban, Unban, Broadcast and check user status~ (Done)
- [x] ~Fix `/chatcast` Command~ (Done)


# Deployment
Before You Deploy make sure you Starred & Forked **[This Repo!](https://github.com/deshadeeth-thisarana/Shadowmusic)** 🤗️


## The Easy Way ⚡️

### With Heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/deshadeeth-thisarana/ShadowMusic)

### With Zeet
<a href="https://zeet.co/new/template/itz-fork/yeah-my-man"><img src="https://user-images.githubusercontent.com/77770753/119371372-fe917900-bcd3-11eb-8db5-f5e8063cdd1c.jpg" width="94" height="28"></a>


#### Get Pyrogram String Session
<a href="https://replit.com/@IamHirusha/GetPyroSessionVC"><img src="https://img.shields.io/badge/Run-Repl.it-white?style=for-the-badge&logo=repl.it"></a>


## Support!
Facing Problems While Deploying or Using? **[Read How To Deploy](https://github.com/Itz-fork/Callsmusic-Plus/wiki/How-To-Deploy-This!)**
or Ask Me In **[Support Group](https://t.me/GangOfFriends)**


### Config Vars 😂,

 `SESSION_NAME` - Your Pyrogram String Session!</br>
 `BOT_TOKEN` - Your Bot Token</br>
 `API_ID` - Your API ID</br>
 `API_HASH` - Your API HASH</br>
 `BOT_OWNER` - Your Telegram Id</br>
 `USER_ACCNAME` - Your bot's streamer account username without "@" ! </br>
 `SUDO_USERS` - Sudo User's ID</br>
 `LOG_CHANNEL` - Log Channel Where Bot Logs Go!</br>
 `BOT_USERNAME` - Your Bot's Username</br>
 `DURATION_LIMIT` - Max Time Limited For a song!</br>
 `ARQ_API_KEY` - Your ARQ api key! Get your own at [ARQ Bot](https://t.me/ARQRobot)</br>
 `DATABASE_URL` - Your MongoDB Url</br>
 `HEROKU_APP_NAME` - Your Heroku App Name! (If you used Heroku)</br>
 `HEROKU_API_KEY` - Your Heroku Api Key! (If you used Heroku)

**[How To Get Config Vars? 🤔 Read This!](https://github.com/Itz-fork/yeah-my-man/wiki/How-To-Deploy-This!)**


# The Hard Way!

## Deploy In Your PC (or whatever)

#### For Ubuntu Based OS

**First run this command** - ``` sudo apt update ```

- Install Python,
```
sudo apt install software-properties-common
```
```
sudo add-apt-repository ppa:deadsnakes/ppa
```
```
sudo apt install python3.9
```

- Install ffmpeg,
```
sudo apt install ffmpeg
```

- Install Git,
```
sudo apt install git
```

- Clone This Repo, 
```
git clone https://github.com/Itz-fork/Callsmusic-Plus
```

- Enter File Dir; 
```
cd Callsmusic-Plus
```

- Install Other Requirements, 
```
pip3 install -r requirements.txt
```

- Go to **config.py** and edit it this with **[your own values](https://github.com/Itz-fork/yeah-my-man/wiki/How-To-Deploy-This!)**

- Finally Let's run the bot, 
```
python3 main.py
```


**For guide on other OS check [This wiki page](https://github.com/Itz-fork/yeah-my-man/wiki/Install-On-Other-OS)**

### Requirements

- FFmpeg
- Python 3.7+

### Config

Copy `example.env` to `.env` and fill it with your credentials.


### Using Docker

1. Build:
   ```bash
   docker build -t musicplayer .
   ```
2. Run:
   ```bash
   docker run --env-file .env musicplayer
   ```


## Credits

- **[Deshadeeth Thisarana](github.com/deshadeeth-thisarana/) ~ Owner**
- **[CallsMusic](https://github.com/callsmusic/callsmusic) ~ This is the base Repo! ❤️**
- **[Roj](https://github.com/rojserbest) & [Marvin](https://github.com/BlackStoneReborn)** : development
- **[Laky](https://github.com/Laky-64) & [Andrew](https://github.com/AndrewLaneX)** : PyTgCalls
- **Mr Dark prince**
- **TeamDaisyX**
- **TheHamkerCat**
- **Abirhasan2005**
- **DevsExpo**
- **N A C CREATIVE**: For Voice Chat Link Command!


## License

### GNU General Public License v3.0
[Read more](http://www.gnu.org/licenses/#GPL)
