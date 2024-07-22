## 0x13-firewall
* published by Maxius(Mark) shija
* Date: 22 July 2024

# Introduction
In this project I ws introduced to the concept of installing firewall into my webserver serving www.shoponbest.tech
## A Fiirewall
- this is the software or hardware used for securing the system. it works by:
- filtering outgoing and incoming traffic

* There are two types of firewall known as :Network and host-based firewall

### Installation
- we use sudo apt-get install ufw  to install a firewall as

Note: Be very careful with firewall rules! For instance, if you ever deny port 22/TCP and log out of your server, you will not be able to reconnect to your server via SSH, and we will not be able to recover it. When you install UFW, port 22 is blocked by default, so you should unblock it immediately before logging out of your server.
