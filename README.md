# License-API-System (python 3.9.12)
## Install required packages by running this command:
```
pip3 install -r requirements.txt
```

## Installation guide
### 1. MySQL
To create this project I used free mysql service [RemoteMySQL](https://remotemysql.com/) its fast enough to store and make operations on small amount of data (up to 100mb). But u can use [XAMPP](https://www.apachefriends.org/) if you use windows/macos/linux its completely free. When its done sign in to mysql root user and create database named ***licensesystem*** then import **sql.sql** file.
### 2. API
Open ***api.py*** file and edit mysql login credentials:

![](https://i.imgur.com/VI6JWgs.png)

When this step is done run api script by running this command:
```
python3 api.py
```
### 3. Discord Bot
Final but not required step is running simple discord bot.
To do this open ***config.json*** file in **/bot directory** and put your discord bot token.

![](https://i.imgur.com/UBMIg3y.png)

Start discord bot by running this command:
```
python3 bot.py
```

Also I recommend to change secretkey used to correctly perform api requests. To change it simply replace ***skey*** value in ***secretkey*** table to different one.

![](https://i.imgur.com/rk9eXbe.png)

#### **Discord bot commands:**

![](https://i.imgur.com/C55uLaP.png)

![](https://i.imgur.com/uQK2n6G.png)


