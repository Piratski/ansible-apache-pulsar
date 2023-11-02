## Requiered for install Apache Pulsar

1. Add actual rpm package JDK and tar.gz apache pulsar in dir files
2. Change all needs vars for Apache Pulsar in inventory/groups_vars/all.yml
3. Add all your needs hosts to inventory/hosts.inventory

## Command for start playbook from /path/to/repo/ansible-apache-pulsar

```
ansible-playbook -i inventory/hosts.inventory setup_apache_Pulsar.yml
```
