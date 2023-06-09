[![CircleCI](https://circleci.com/gh/ansible-roles-mamono210/passenger.svg?style=svg)](https://circleci.com/gh/ansible-roles-mamono210/passenger)

Role Description
=========

Install [passenger](https://www.phusionpassenger.com)  on CentOS Stream 8.

Requirements
------------

Before running this role, the following packages must be installed on the target system.

* [Apache HTTP Server](https://httpd.apache.org)
* [Ruby](https://www.ruby-lang.org)

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
    - passenger
```

License
-------

BSD
