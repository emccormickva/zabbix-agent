# Zabbix Agent Installer playbook for Centos 7


### Usage

This playbook is used to quickly install a Zabbix Agent on a batch of hosts. 

1) Update the roles/install/templates/zabbix-agentd.conf <server-name> to reflect your Zabbix server name or IP
2) Run ansible-playbook -i <some-inventory> main.yml

Modify at will. Provided with no warranties. Yadda yadda yadda.


