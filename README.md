<h2 align="center">Telegram Streamer Bot </h2>
<p>
Telegram bot for stream music or video on telegram, 
powered by <a href="https://github.com/pytgcalls/pytgcalls">PyTgCalls</a>
and <a href="https://github.com/pyrogram/pyrogram">Pyrogram</a>
</p>

<div align="center">
    <a href="https://github.com/fjgaming212/Bot-Music"><img src="https://img.shields.io/github/repo-size/fjgaming212/Bot-Music?logo=github"></a> <br>
    <a href="https://github.com/fjgaming212/Bot-Music"><img src="https://img.shields.io/github/forks/fjgaming212/Bot-Music?logo=github"></a>
    <a href="https://github.com/fjgaming212/Bot-Music"><img src="https://img.shields.io/github/stars/fjgaming212/Bot-Music?logo=github"></a>
</div>


<h3>Features</h3> 
<ul>
    <li>Playlist features</li>
    <li>Multi Language</li>
    <li>Maintained</li>
    <li>Less environment variables</li>
</ul>

<h3>Telegram</h3>
<ul>
    <a href="https://t.me/BotMusicUpdates"><img alt="SChannel" src="https://img.shields.io/badge/Channel-blue.svg?logo=telegram"></a> <br/>
    <a href="https://t.me/BotMusicChat"><img alt="Support" src="https://img.shields.io/badge/Support-blue.svg?logo=telegram"></a> <br/>
</ul>

<h3>Deploy to Heroku </h3>
<div>
    <a href="https://dashboard.heroku.com/new?button-url=https://github.com/fjgaming212/Bot-Music&template=https://github.com/Zeenada/z-Music"><img src="https://www.herokucdn.com/deploy/button.svg"></a>
</div>

### Deploy to VPS
```
$ sudo su
# apt-get update && apt-get upgrade -y
# apt-get install curl
# curl -sL https://deb.nodesource.com/setup_16.x | bash - 
# apt-get install ffmpeg python3-pip python3-virtualenv nodejs -y 
# git clone https://github.com/fjgaming212/Bot-Music && cd Bot-Music
# virtualenv venv && . venv/bin/activate 
# pip3 install --no-cache-dir -r requirements.txt 
# cp sample.env .env 
# nano .env # fill it with your env 
# python3 main.py
```

# Credits ©
* [Abdul](https://github.com/DoellBarr/solidmusic) - Solid Music
