# SuperHuman - UserBot
A stable pluggable Telegram userbot, based on Telethon.

<p align="center">
  <img src=".dropbox.com/s/d7mx1gyolvne77t/20210226_213110.jpg?dl=0" alt="SuperHuman_userbot">
</p>

[![Stars](https://img.shields.io/github/stars/TeamUltroid/Ultroid?style=flat-square&color=green)](https://github.com/TeamUltroid/Ultroid/stargazers)
[![Forks](https://img.shields.io/github/forks/TeamUltroid/Ultroid?style=flat-square&color=green)](https://github.com/TeamUltroid/Ultroid/fork)
[![Python Version](https://img.shields.io/badge/Python-v3.9-blue)](https://www.python.org/)
[![Contributors](https://img.shields.io/github/contributors/TeamUltroid/Ultroid?style=flat-square&color=green)](https://github.com/TeamUltroid/Ultroid/graphs/contributors)
[![License](https://img.shields.io/badge/License-AGPL-blue)](https://github.com/TeamUltroid/Ultroid/blob/main/LICENSE)
[![Size](https://img.shields.io/github/repo-size/TeamUltroid/Ultroid?style=flat-square&color=green)](https://github.com/TeamUltroid/Ultroid/)

<details>
<summary>More Info</summary>
<br>
  <b>Documentation</b> - <a href="https://ultroid.netlify.app">ultroid.netlify.app</a>  <br />
</details>

# Deploy 
- [Heroku](https://github.com/TeamUltroid/Ultroid#Deploy-to-Heroku)
- [Local Machine](https://github.com/TeamUltroid/Ultroid#Deploy-Locally)

## Deploy to Heroku
- Get your `API_ID` and `API_HASH` from [here](https://my.telegram.org/)    
- Get your `SESSION` from [here](https://repl.it/@TeamUltroid/UltroidStringSession#main.py).   
and click the below button!  <br />  

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

## Deploy Locally
- Get your `API_ID` and `API_HASH` from [here](https://my.telegram.org/)
- Get your `REDIS_URI` and `REDIS_PASSWORD` from [here](https://redislabs.com), tutorial [here](./resources/extras/redistut.md).
- Clone the repository: <br />
`git clone https://github.com/TeamUltroid/Ultroid.git`
- Go to the cloned folder: <br />
`cd Ultroid`
- Create a virtual env:   <br />
`virtualenv -p /usr/bin/python3 venv`   
`. ./venv/bin/activate`
- Install the requirements:   <br />
`pip install -r requirements.txt`   
- Generate your `SESSION`:   
`bash sessiongen`
- Fill your details in a `.env` file, as given in [`.env.sample`](https://github.com/TeamUltroid/Ultroid/blob/main/.env.sample).    
(You can either edit and rename the file or make a new file.)
- Run the bot:   
`bash resources/startup/startup.sh`

Made with 💕 by [@TheName_Is_VISH_0](https://t.me/@SuperHuman_Userbot). <br />

# Credits
* [VISH](https://github.com/Elon-Musk-fan/) for [Telethon](https://github.com/LonamiWebs/Telethon)

