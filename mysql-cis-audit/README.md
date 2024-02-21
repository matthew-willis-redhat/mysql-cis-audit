mysql-cis-audit
=========

Audit MySQL databases with a selected set of CIS benchmark rules.

Requirements
------------

Collections:

    - community.mysql

Role Variables
--------------

    mysql_login_user:
    mysql_login_password:

Dependencies
------------

N/A

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      tasks:
        - ansible.builtin.include_role:
            name: mysql-cis-audit 

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
