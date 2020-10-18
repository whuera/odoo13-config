![technology Gradle](https://img.shields.io/badge/technology-Gradle-blue.svg)
![homebrew](https://img.shields.io/homebrew/v/cake)
![Open Collective sponsors](https://img.shields.io/opencollective/sponsors/shields)
[![GitHub forks](https://img.shields.io/github/forks/whuera/odoo13-config)](https://github.com/whuera/odoo13-config/network)
[![GitHub issues](https://img.shields.io/github/issues/whuera/odoo13-config)](https://github.com/whuera/odoo13-config/issues)
[![GitHub license](https://img.shields.io/github/license/whuera/odoo13-config)](https://github.com/whuera/odoo13-config/blob/master/LICENSE)


# Install odoo13 Enterprice in Google Cloud Instance / Linux Ubuntu
configuraciones para instalar odoo13 enterprice

install Odoo ver. 13

## follow next steps:
1. if exists previus installation of Odoo or last instalaltion not found, down odoo server: /odoo/odoo-server stop
2. change python version type this commands: 
3. sudo add-apt-repository ppa:jonathonf/python-3.6
4. sudo apt update
5. sudo apt install python3.6
6. then delete old version of python, type this commands:
7. sudo rm /usr/bin/python
8. sudo ln -s /usr/bin/python3 /usr/bin/python
9. verify python version:
10. python -V
11. you can see in screen result: version 3.6
12. then, creat directory:
13. mkdir /var/lib/odoo
14. then type this command:
15. sudo apt --fix-broken install
16. download this repo this file: "odoo_install.sh" and execute: "odoo_install.sh" note: this file is fixed of original version
17. you can using: sh odoo_install.sh or ./odoo_install.sh

reference:
https://github.com/Yenthe666/InstallScript
