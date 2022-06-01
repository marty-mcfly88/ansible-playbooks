# ansible-playbooks

## How to run these playbooks
* If you don't have ssh keys setup yet, use a common account and pass the -kK flag to have it prompt for auth to that account.
* Example:
** > ansible-playbook system_config.yml -kK

## How to get devices into an inventory so that you can run a playbook on them.
* Add their ip addresses to /etc/ansible/hosts
