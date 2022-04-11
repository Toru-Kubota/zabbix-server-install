# Install Zabbix Server
## Requirements
* AlmaLinux release 8.5
* ZABBIX Server 5.0

## Installation
### Change password of following var
group_vars/zabbix_server.yml

mariadb_root_password: 
mariadb_zabbix_password: 

### Run playbook
ansible-playbook -i inventory.ini Zabbix-Server-Setting.yml