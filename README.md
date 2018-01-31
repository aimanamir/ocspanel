OcsPanels
=========
Simple and lightweight panel for Reseller SSH based on Webmin API, 100% free.

Features
-------
* **Sistem Deposit** : Seller cukup Deposit, sudah bisa create Account SSH sendiri.
* **Remote Webmin** : cukup 1 panel bisa dipakai untuk banyak VPS.

Requirements
---------

##### Hosting
* PHP versi 5.3.4 keatas.
* MySQL versi 5.0.0 keatas.

##### VPS
* Webmin
* Perl XML::Parser Module (biasa otomatis terinstall bersama webmin)

Installation
------------
* Debian: https://sshkuat.blogspot.my/2017/06/tutorial-install-ocs-panel-2017.html?m=1

Gantikan

`cd /home/vps/public_html
git init
git remote add origin https://github.com/stevenindarto/OCSPanel.git
git pull origin master

chmod 777 /home/vps/public_html/config
chmod 777 /home/vps/public_html/config/config.ini
chmod 777 /home/vps/public_html/config/route.ini`

dengan

`cd /home/vps/public_html
git init
git remote add origin https://github.com/aimanamir/ocspanel.git
git pull origin master

chmod 777 /home/vps/public_html/config
chmod 777 /home/vps/public_html/config/config.ini
chmod 777 /home/vps/public_html/config/route.ini`
