# Workstation setup

Ansible playbooks for Arch and Ubuntu.

Run with

```shell
# get dependencies
ansible-galaxy install -r requirements.yml
# run with
ansible-playbook -K ubuntu.yml
# or (untested)
ansible-playbook -K arch.yml
```