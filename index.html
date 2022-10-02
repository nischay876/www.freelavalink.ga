#!/bin/bash
set -e
echo -e "\e[32m
# # # # # # # # # # # # # # # # # # # # # # # # # # # # #
#              lavalink Installation Script             #
#         Created and maintained by nischay876          #
#       Author @nischay876 | https://nischay.ovh        #
#           https://discord.freelavalink.ga             #
#              Protected by MIT License                 #
#        Copyright (C) 2022 - 2022, nischay876.         #
#     https://github.com/nischay876/lavalink-install    #
#       This Script only works on Ubuntu & Debian       #
# # # # # # # # # # # # # # # # # # # # # # # # # # # # #\e[0m"

# Check Sudo #
if [[ $EUID -ne 0 ]]; then
    echo -e "\e[32m* This script must be executed with root privileges (sudo).\e[0m" 1>&2
    exit 1
fi

# proceed ?
while true; do
RESET="\e[0m"
GREEN="\e[32m"
read -p "$(echo -e $GREEN"\n* Do you want to proceed? (Y/N) | (y/n)"$RESET)" yn
case $yn in
	[yY] ) echo -e "\e[32m* ok, we will proceed\e[0m";
		break;;
	[nN] ) echo -e "\e[32m* exiting...\e[0m";
		exit;;
	* ) echo -e "\e[32m* invalid response\e[0m";;
esac
done
echo -e "\e[32m* doing stuff...\e[0m"
sudo apt update > /dev/null 2>&1

# Check Curl #
if ! [ -x "$(command -v curl)" ]; then
    echo -e "\e[32m* curl is required in order for this script to work.\e[0m"
    echo -e "\e[32m* Installing curl with (sudo apt install -y curl)\e[0m"
    sudo apt install -y curl > /dev/null 2>&1
fi

# Check NodeJS #
if ! [ -x "$(command -v node)" ]; then
    echo -e "\e[32m* nodejs is required in order for this script to work.\e[0m"
    echo -n -e "\e[32mWhat NODE.JS version you want to install? (just add number from 10-18, anything other than number will brake the script)\e[0m"
    read NodeJsVer
    if [[ -n "$NodeJsVer" ]]
    then
        in=$NodeJsVe
    fi
    echo -e "\e[32m* You selected NodeJS version $in \e[0m"
    echo -e "\e[32m* Installing NodeJS with (sudo apt install -y nodejs)\e[0m"
    curl -sL https://deb.nodesource.com/setup_$in.x | sudo -E bash - > /dev/null 2>&1 && sudo apt install -y nodejs > /dev/null 2>&1
fi

# Check NPM #
if ! [ -x "$(command -v npm)" ]; then
    echo -e "\e[32m* npm is required in order for this script to work.\e[0m"
    echo -e "\e[32m* Installing npm with (sudo apt install -y npm)\e[0m"
    sudo apt install -y npm > /dev/null 2>&1
fi

# Check Wget #
if ! [ -x "$(command -v wget)" ]; then
    echo -e "\e[32m* npm is required in order for this script to work.\e[0m"
    echo -e "\e[32m* Installing wget with (sudo apt install -y wget)\e[0m"
    sudo apt install -y wget > /dev/null 2>&1
fi

# Check Java #
if ! [ -x "$(command -v javac)" ]; then
    echo -e "\e[32m* java is required in order for this script to work.\e[0m"
    echo -e "\e[32m* Installing java with (sudo apt install -y default-jdk)\e[0m"
    sudo apt install -y default-jdk > /dev/null 2>&1
fi

# Check Pm2 #
if ! [ -x "$(command -v pm2)" ]; then
    echo -e "\e[32m* pm2 is required in order for this script to work.\e[0m"
    echo -e "\e[32m* Installing pm2 with (sudo npm install pm2 -g)\e[0m"
    sudo npm install pm2 -g > /dev/null 2>&1
fi

# Installing lavalink
echo -e "\e[32m* Starting lavalink installation\e[0m"
echo -e "\e[32m* Making freelavalink directory at ~/freelavalink\e[0m"
mkdir ~/freelavalink && cd ~/freelavalink
echo -e "\e[32m* Downloading Lavalink.jar\e[0m"
wget https://github.com/Cog-Creators/Lavalink-Jars/releases/latest/download/Lavalink.jar > /dev/null 2>&1
echo -e "\e[32m* Downloading application.yml\e[0m"
wget https://gist.githubusercontent.com/nischay876/88c080f8eeb07d37daed1aa2314170c0/raw/application.yml > /dev/null 2>&1
echo -e "\e[32m* Downloading config.json\e[0m"
wget https://gist.githubusercontent.com/nischay876/88c080f8eeb07d37daed1aa2314170c0/raw/config.json > /dev/null 2>&1
echo -e "\e[32m* Lavalink installation completed\e[0m"
echo -e "\e[32m* Thank You For Using This Script To Install Lavalink\e[0m"
echo -e "\e[32m
# # # # # # # # # # # # # # # # # # # # # # # # # # # # #
#       Author @nischay876 | https://nischay.ovh        #
#      Discord - https://discord.freelavalink.ga        #
#        Copyright (C) 2022 - 2022, nischay876.         #
#     https://github.com/nischay876/lavalink-install    #
# # # # # # # # # # # # # # # # # # # # # # # # # # # # #\e[0m"

# run lavalink rn ?
while true; do
RESET="\e[0m"
GREEN="\e[32m"
read -p "$(echo -e $GREEN"\n* Do you want to run lavalink right now? (Y/N) | (y/n)"$RESET)" yn
case $yn in
	[yY] ) echo -e "\e[32m* ok, running Lavalink | Use (pm2 ls) to view lavalink status\e[0m"
           echo -e "\e[32m* (lavalink) is Lavalink's Password\e[0m"
           mypubip=$(curl ipaddress.sh)
           echo -e "\e[32m* Lavalink Started at http://$mypubip:2333 | http://127.0.0.1:2333\e[0m"
		break;;
	[nN] ) echo -e "\e[32m* exiting...\e[0m";
		exit 1;;
	* ) echo -e "\e[32m* invalid response\e[0m";;
esac
done
pm2 start ~/freelavalink/config.json
exit 1
