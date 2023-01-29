<h2 align="center"><u>CamHacker</u></h2>

![Hack anyone's camera and get images](https://github.com/ferlo-369-github/CamHacker/raw/main/files/banner.png)
<h4 align="center"> Hack anyone's camera and get images!</h4>

<p align="center">
    <img src="https://img.shields.io/badge/Version-1.5-blue?style=for-the-badge&color=blue">
    <img src="https://img.shields.io/github/stars/ferlo-369-github/CamHacker?style=for-the-badge&color=magenta">
    <img src="https://img.shields.io/github/forks/ferlo-369-github/CamHacker?color=cyan&style=for-the-badge&color=purple">
    <img src="https://img.shields.io/github/issues/ferlo-369-github/CamHacker?color=red&style=for-the-badge">
    <img src="https://img.shields.io/github/license/ferlo-369-github/CamHacker?style=for-the-badge&color=blue">
<br>
    <img src="https://img.shields.io/badge/Author-ferlo-369-github-green?style=flat-square">
    <img src="https://img.shields.io/badge/Open%20Source-Yes-orange?style=flat-square">
    <img src="https://img.shields.io/badge/Maintained-Yes-cyan?style=flat-square">
    <img src="https://img.shields.io/badge/Written%20In-Shell-blue?style=flat-square">
</p>

### [+] Description
CamHacker is a phishing tool. It will generate a link. If anyone opens the link and permits camera access, his/her photo will be captured and sent to you!




### [+] Installation

 - `git clone https://github.com/ferlo-369-github/CamHacker`
 - `cd CamHacker`

For termux, use additional command `termux-setup-storage`
 - `bash ch.sh`

##### Or Run Directly
```
wget https://raw.githubusercontent.com/ferlo-369-github/CamHacker/main/ch.sh && bash ch.sh
```

### Docker

 - `sudo docker pull ferlo-369-github/camhacker`
 - `sudo docker run --rm -it --name camhacker ferlo-369-github/camhacker`
 - `sudo docker cp camhacker:/CamHacker imgfiles` [Run this on another terminal to copy received image from docker to imgfiles folder keeping container open]

##### Usage
```
Usage: bash ch.sh [-h] [-o OPTION] [-p PORT] [-t TUNNELER] [-u] [-nu]

Options:
  -h, --help                           Show this help message and exit
  -o OPTION, --option OPTION           Index of the template
  -p PORT, --port PORT                 Port of CamHacker's Server (Default: 8080)
  -t TUNNELER, --tunneler TUNNELER     Name of the tunneler for url shortening (Default: cloudflared)
  -d DIRECTORY, --directory DIRECTORY  Directory where images will be saved
  --update(-u), --no-update (-nu)      Check for update (Default: true)
```


### [+] Features
 - Three Templates
 - Get IP, Location, Device type and Browser
 - Concurrent triple tunneling (Ngrok, Cloudflared and Loclx)
 - Choose where to save images(custom directory) 
 - Error Diagnoser
 - Argument support for templates, tunnelers and directory


### [+] Preview 
![Hack anyone's camera and get images](https://github.com/ferlo-369-github/CamHacker/raw/main/files/ch.gif)

### [+] Depenencies
 - `php`
 - `curl`
 - `wget`
 - `unzip`

All of the necessary depenencies will be installed automatically in first run!

### [+] Note
You need to use good (not mini version like opera mini) browsers as chrome/brave/mozila to get image captured. Although some browsers can block this CamHacker, however it works in most devices.


### [+] Disclaimer 
***This tool is developed for educational purposes. Here it demonstrates how camera phishing works. If anybody wants to gain unauthorized access to someones camera, he/she may try out this at his/her own risk. You have your own responsibilities and you are liable to any damage or violation of laws by this tool. The author is not responsible for any misuse of CamHacker!***



