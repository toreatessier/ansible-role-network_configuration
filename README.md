# Ansible Role : newtork_configuration

Ansible Role for Jakarta Project's network configuration.

Requirements
------------

Cisco Catalyst 2960 with minimal install SSH enabled

Example Playbook
----------------

```
- name: Deploy network configuration for Jakarta
  hosts: "{{hosts}}"
  remote_user: ansible
  tasks:
  - import_role:
      name: network_configuration
      tasks_from: install
```

Author Information
------------------

* **Toréa TESSIER** - <torea.tessier@reseau.eseo.fr> - [Jakarta Project](https://192.168.4.16/Equipe_1_Jakarta/)