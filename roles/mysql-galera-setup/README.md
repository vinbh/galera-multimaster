Role Name
=========

Install mysql on a multi-mster setup

Requirements
------------
None, ansible 2.11 is used here. Check ansible docs for any issues.

Role Variables
--------------

host_ip


Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:
        ---

        - hosts: mysql
          become: true
          roles:
            - { role: mysql-galera-setup }
          tags:
            - mysql_galera

License
-------

BSD

Author Information
------------------

VB
