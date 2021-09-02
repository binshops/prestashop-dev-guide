# Prestashop Developer Guide


### How to setup a fully ready [Prestashop](https://github.com/PrestaShop) developing enviroment?
***
#### *[Binshops](https://github.com/binshops)* team recommendation set to help [Prestashop](https://github.com/PrestaShop) developers setup a handy enviroment fast and easy.
***
*This guide gets updated mostly based on team developers expirence. But we also accept your suggestions.*
***
### Setup An Ubuntu Running Machine
1. [Download](https://ubuntu.com/download/desktop) and [Install](https://ubuntu.com/tutorials/install-ubuntu-desktop#1-overview) Ubuntu.
***
### Install Softwares And Packages
1. [Apache](https://www.digitalocean.com/community/tutorials/how-to-install-the-apache-web-server-on-ubuntu-20-04)
2. [MySQL](https://www.digitalocean.com/community/tutorials/how-to-install-mysql-on-ubuntu-20-04)
   1. Must create new user. root user can not be accessed remotely(in phpmyadmin)
3. [php7.4](https://www.digitalocean.com/community/tutorials/how-to-install-php-7-4-and-set-up-a-local-development-environment-on-ubuntu-20-04)
4. MySQL GUI (Choose one)
   1. [phpMyAdmin](https://www.phpmyadmin.net/downloads/)
      1. Download zip
	  2. Extract in `/var/www/html/`
	  3. Grant all access to `/phpmyadmin/` with this terminal command `sudo chmod -R 777 /phpmyadmin/`
   4. MySQL Workbench
3. IDE (Choose one)
   1. [Visual Studio Code](https://code.visualstudio.com/download)
   2. [PHP Storm](https://www.jetbrains.com/phpstorm/download/)
4. Debugger(Choose one)
   1. Xdebug for Visual Studio Code
   2. Xdebug for PHP Storm
5. [PhpPsInfo](https://github.com/PrestaShop/php-ps-info)
PrestaShop system requirements checker
1. [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
2. [GitKraken](https://support.gitkraken.com/how-to-install/)
***