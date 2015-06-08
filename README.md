ansible-role-epel
=========

Make the EPEL repository available via YUM.

Requirements
------------

This role has been tested on EL6 hosts. Support for EL7 is anticipated with a future release.

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

- hosts: servers
  roles:
    - { role: bitmotive.ansible-role-epel, tags: "epel,common" }

License
-------

MIT
