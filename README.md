# ansible-pi
My personal collection of different roles and playbooks to setup, maintain and customize my raspberry pis.

You may find something usefull in this repo for your own need.
Feel free to copy and / or contribute.

# Currently available options
## Ping
Ping the pis
```
ansible-playbook -i inventory.yaml ping-playbook.yaml
```
## Maintenance
Simple apt update & upgrade
```
ansible-playbook -i inventory.yaml maintenance.yaml
```