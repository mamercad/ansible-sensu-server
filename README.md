mamercad.sensu-server
=====================

Stands up a Sensu server on RHEL/CentOS

Warnings
--------

The role puts SELinux into permissive mode and disabled firewalld

Requirements
------------

None

Role Variables
--------------

See the example playbook below, as well as vars/main.yml

Dependencies
------------

None

Example Playbook
----------------

    - hosts:
        - sensu
      roles:
        - mamercad.sensu-server

License
-------

GPLv3

Author Information
------------------

Mark Mercado <mamercad@umflint.edu>
