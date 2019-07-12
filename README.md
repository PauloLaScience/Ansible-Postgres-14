# Ansible-Postgres-10
Ansible project to deploy and upgrade Postgresql 10

tests
ansible-playbook installpg95.yml -i tests/inventory.txt --user=osboxes --extra-vars "ansible_sudo_pass=osboxes.org"
