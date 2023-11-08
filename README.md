vector v 1.0.4
=========

This role can install vector on EL

Role Variables
--------------

|vars |description |
|-----|------------|
|vector_version |Version of vector to install |


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: vector }

Tags  
-------
- vector

Tests
-------

Molecule with docker driver:  
```
molecule test -s default
```

License
-------

MIT

Author Information
------------------

aleks sh
