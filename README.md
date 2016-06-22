freitag.postfix
===============
Ansible role to install and configure postfix.

Requirements
------------
None

Role Variables
--------------
``postfix_fqdn``: set postfix domain (it will go to ``/etc/mailname``).

Dependencies
------------
None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: freitag.postfix, postfix_fqdn: mail.example.com }

License
-------
GPLv3

Author Information
------------------
Gil Forcada Codinachs (der Freitag).
