## Features
Install ZABBIX server for AlmaLinux 8

## Require
Ansible on AlmaLinux 8

## Install

Set the following variables in **group_vars/zabbix_server.yml**
| variable| explanation |
| ------ | ------ |
| mariadb_root_password | mariadb root password|
| mariadb_zabbix_password | mariadb zabbix user password|

Run ansible playbook
```sh
ansible-playbook -i inventory.ini Zabbix-Server-Setting.yml
```