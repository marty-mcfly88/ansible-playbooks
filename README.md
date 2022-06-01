# ansible-playbooks

## How to run these playbooks
* If you don't have ssh keys setup yet, use a common account and pass the -kK flag to have it prompt for auth to that account.
* Be sure to connect to the host from the ansible server via ssh first. This will add the fingerprint and allow use of '-kK'.
* Example:
** > ansible-playbook system_config.yml -kK

## How to get devices into an inventory so that you can run a playbook on them.
* Add their ip addresses to /etc/ansible/hosts
