[![CircleCI](https://circleci.com/gh/ansible-roles-mamono210/fortune/tree/main.svg?style=svg)](https://circleci.com/gh/ansible-roles-mamono210/fortune/tree/main)

Role Description
=========

Installs [Fortune](http://www.thinkyhead.com/fortune) for CentOS7.

Requirements
------------

EPEL installed before running this role.

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

```YAML
---
- hosts: all
  become: true
  roles:
    - geerlingguy.repo-epel
    - fortune
```

License
-------

BSD
