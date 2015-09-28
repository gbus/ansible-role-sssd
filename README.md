ansible-role-sssd
=========

Configures sssd. Quite untested in it's current state.

Requirements
------------

 - Certificate needs to be from TERENA (so probably others or TERENA3 does not work)
  - This should be a parameter

Role Variables
--------------

See:
 - defaults/main.yml and vars/main.yml
 - templates/sssd-example.conf.j2
 - ldap\_password - this variable needs to have the password of the bind-account.

Dependencies
------------


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ansible-role-sssd }

License
-------

MIT

Author Information
------------------

Originally written by Marco Passerini https://github.com/mpasserini . Moved into public Github by Johan Guldmyr @ CSC
