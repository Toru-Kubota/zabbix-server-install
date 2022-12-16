## 内容


**ZABBXIXインストール用のAnsible Playbookです。**

![Zabbix_logo](https://user-images.githubusercontent.com/102895466/208058847-00d28fbe-62a6-48af-89a3-27407dce8d51.png)


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
