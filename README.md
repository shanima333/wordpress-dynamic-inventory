# Ansible playbook to create EC2 instance and 

Playbook to :
- create EC2 instance
- update the inventory dynamically
- install wordpress

using 2 roles
- apache-mysql
- wordpress-httpd

Roles:
- apache-mysql : To install apache and mariadb server
- wordpress-httpd: install wodpress



## Folder
key - to keep the newaly created private keys

## ansible.cfg
Custom configuration file for this project

## ec2_wordpress.yaml

This playbook will 
- create a key pari 
- copy the private key to local folder key under working directoy
- Launch an instance with the newly created key pair
-  Add the host details on hosts file
-  Add new instance to host group
