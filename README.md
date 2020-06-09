ansible-dns
=====================

This role automates the process of installing DNS server on CentOS 7.

Requirements
------------

1) Must be a fresh CentOS 7 minimal installation
2) Static network configuration must be already set

Role Variables
--------------

Modify the variables in vars/main.yml to suit your environment.

Dependencies
------------


Example Playbook
----------------

Create an inventory file similar below:

Create playbook similar below:

    # vi site.yml

    --- 
    - hosts: server
      roles:
        - harpreet.dns

Then run as follows:

    # ansible-playbook -i inventory site.yml

License
-------

