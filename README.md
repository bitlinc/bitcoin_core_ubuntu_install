# linux_install

#!/usr/bin/env bash

apt update
apt upgrade
apt install ufw
sudo ufw default allow outgoing
sudo ufw default allow incoming
ufw enable


sudo apt-add-repository ppa:bitcoin/bitcoin
sudo apt-get update
sudo apt-get install bitcoin-qt
