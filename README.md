[![Build Status](https://travis-ci.org/bytepark/ansible-base.svg?branch=master)](https://travis-ci.org/bytepark/ansible-base)

ansible-base
=========

Ansible role to install base settings for a server

Requirements
------------

No further requirements besides bash.

Role Variables
--------------

```
server:
     hostname: "myhost"
     timezone: "Europe/Berlin"
     locale: de_DE.UTF-8
```

Dependencies
------------

No dependencies.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: bytepark.base }

License
-------

MIT

Author Information
------------------

bytepark / 2018.

