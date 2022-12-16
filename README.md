## 環境
* Almalinux 8
* ZABBIX 5

## パラメーター
Playbook実行前に```group_vars/zabbix_server.yml```の下記パラメーター変更して下さい。

デフォルトは```passsword```に設定されます。

| 変数| 説明 |
| ------ | ------ |
| mariadb_root_password | mariadb root password|
| mariadb_zabbix_password | mariadb zabbix user password|

## 使用方法
詳しいやり方は[Zabbixインストール用Ansible Playbook(EC2)](https://qiita.com/tkubota/items/e395e20bb14acf35be42)にあります。
