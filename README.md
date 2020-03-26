[![](https://github.com/ansible-roles-matsumura/fortune/workflows/Build/badge.svg)](https://github.com/ansible-roles-matsumura/fortune/actions?query=workflow%3ABuild)
[![](https://github.com/ansible-roles-matsumura/fortune/workflows/Lint/badge.svg)](https://github.com/ansible-roles-matsumura/fortune/actions?query=workflow%3ALint)

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