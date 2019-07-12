# Ansible-Postgres-10
## Description
Ansible project to deploy and upgrade Postgresql 10

## Sample
Run this after installing 2 targets centos7 from [osboxes.org](https://www.osboxes.org)
```
ansible-playbook installpg95.yml -i tests/inventory.txt --user=osboxes --extra-vars "ansible_sudo_pass=osboxes.org"
```
