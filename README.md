# Ansible-Postgres-10
## Description
Ansible project to deploy and upgrade Postgresql 10

## Sample
Run this after installing 2 targets centos7 from [osboxes.org](https://www.osboxes.org)

```
ansible-playbook installpg10.yml -i tests/inventory.txt --user=osboxes --extra-vars "ansible_sudo_pass=osboxes.org" --extra-vars "postgres_data_dir=/var/lib/pgsql/10/data"
```

Or, using roles,

```
ansible-playbook instwrolespg10.yml -i tests/inventory.txt --user=osboxes --extra-vars "ansible_sudo_pass=osboxes.org" --extra-vars "postgres_data_dir=/var/lib/pgsql/10/data"
```

Pls note, this is the old syntax for using roles. New syntax coming soon.

You can also test with vagrant and libvirt if it's installed
Just run:
```
vagrant up
```

## About
Additional ressource now available:

 - contribz

