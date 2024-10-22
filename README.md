<div align="center">
  <img src="20241017_224427.jpg">
</div>

# Tomarket

Auto Claim for [tomarket](http://t.me/Tomarket_ai_bot/app?startapp=0000zW9F) Telegram Bot

# Table of Contents

- [Tomarket](#tomarket)
- [Features](#features)
- [Register](#register)
- [How to Use](#how-to-use)
  - [About Config](#about-config)
  - [About Proxy](#about-proxy)
  - [Windows](#windows)
  - [Linux](#linux)
  - [Termux](#termux)
- [How to Get Data](#how-to-get-data)
- [Run for 24/7](#run-for-247)

# Features

- [x] Auto Claim
- [x] Auto Farm
- [x] Auto Claim referral
- [x] Auto Spin
- [x] Multi Account Support
- [x] Auto Play Game
- [x] Proxy Support

# Register

Click the following url to register: [tomarket](http://t.me/Tomarket_ai_bot/app?startapp=0000zW9F)

# How to Use

## About Config

| Name            | Description                                                                                |
| --------------- | ------------------------------------------------------------------------------------------ |
| interval        | downtime between account                                                                   |
| play_game       | value must bool (true/false) set true for enable auto play game after claim                |
| game_point      | low : minimum earn from play game <br>high : maximum earn from play game                   |
| additional_time | min : minimum addition time for next claim <br> max : maximum addition time for next claim |

## About Proxy

Register on this site to get free proxy : [Here](https://www.webshare.io/?referral_code=dwj0m9cdi4mp)

You can add your proxy list in `proxies.txt` and proxy format is like example below :

Format :

```
http://host:port
http://user:pass@host:port
```

Example :

```
http://127.0.0.1:6969
http://user:pass@127.0.0.1:6969
socks5://127.0.0.1:6969
socks5://user:pass@127.0.0.1:6969
```

## Windows 

1. Make sure you computer was installed python and git.
   
   python site : [https://python.org](https://python.org)
   
   git site : [https://git-scm.com/](https://git-scm.com/)

2. Clone this repository
   ```shell
   git clone https://github.com/zyz-airdrops/tomarket-claimer.git
   ```

3. goto tomarketod directory
   ```
   cd tomarket-claimer
   ```

4. install the require library
   ```
   python -m pip install -r requirements.txt
   ```

5. Edit `data.txt`, input you data token in `data.txt`, find you token in [How to Get Data](#how-to-get-data). One line for one data account, if you want add you second account add in new line!

6. execute the main program 
   ```
   python bot.py
   ```

## Linux

1. Make sure you computer was installed python and git.
   
   python
   ```shell
   sudo apt install python3 python3-pip
   ```
   git
   ```shell
   sudo apt install git
   ```

2. Clone this repository
   
   ```shell
   git clone https://github.com/zyz-airdrops/tomarket-claimer.git
   ```

3. goto tomarketod directory

   ```shell
   cd tomarket-claimer
   ```

4. Install the require library
   
   ```
   python3 -m pip install -r requirements.txt
   ```

5. Edit `data.txt`, input you data token in `data.txt`, find you token in [How to Get Data](#how-to-get-data). One line for one data account, if you want add you second account add in new line!

6. execute the main program 
   ```
   python bot.py
   ```

## Termux

1. Make sure you termux was installed python and git.
   
   python
   ```
   pkg install python
   ```

   git
   ```
   pkg install git
   ```

2. Clone this repository
   ```shell
   git clone https://github.com/zyz-airdrops/tomarket-claimer.git
   ```

3. goto tomarketod directory
   ```
   cd tomarket-claimer
   ```

4. install the require library
   ```
   python -m pip install -r requirements.txt
   ```

5. Edit `data.txt`, input you data token in `data.txt`, find you token in [How to Get Data](#how-to-get-data). One line for one data account, if you want add you second account add in new line!

You can edit the data.txt with `nano`

6. execute the main program 
   ```
   python bot.py
   ```

# How to Get Data

How to enable dev tools on telegram PC : [https://youtu.be/NYxHmck_GjE](https://youtu.be/NYxHmck_GjE)

Watch the following video to get data [https://youtu.be/fdbdt-fEoVg](https://youtu.be/fdbdt-fEoVg)

Javascript code for getting query (user= / query=)

```javascript
copy(decodeURIComponent(sessionStorage.SourceTarget).split('#tgWebAppData=')[1].split('&tgWebAppVersion=')[0]);console.log('data copied !\npaste ctrl + v')
```

# Run for 24/7 

You can run the script bot for 24/7 using vps / rdp. You can use `screen` application in vps linux to running the script bot in background process.
