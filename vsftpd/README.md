vstfpdv installator
=========

Install and start vstfpd

Requirements
------------

apt

Role Variables
--------------

-

Dependencies
------------

-

Example Playbook
----------------

  - name: Launch vsftpd role
    hosts: localhost
    gather_facts: false
    become: true
    roles:
      - vsftpd

License
-------

BSD

Author Information
------------------

@amphyxs
