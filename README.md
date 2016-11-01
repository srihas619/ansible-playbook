# ansible-playbook

This playbook is aimed at doing tasks based on roles that are specified.

## Roles

For now, Only Apache role is specified. It installs apache2 on Ubuntu nodes and changes the default index.html with the one in templates/

## Installation

* Install ansible on your controller node

* Exchange ssh-key between controller node and deployer nodes

* Change IP addresses in inventory.txt

* Run playbook as "ansible-playbook -i inventory.txt playbook.yml"
