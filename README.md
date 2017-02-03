Vagrant Role 
============

Installs Vagrant

Requirements
------------

none

Role Variables
--------------

```
_vagrant_version: "1.9.1"
```

Dependencies
------------

none

Example Playbook
----------------

```YAML
    - hosts: all
      become: yes
      roles:
         - { role: vagrant, _vagrant_version: "1.9.1" }
```

License
-------

BSD
