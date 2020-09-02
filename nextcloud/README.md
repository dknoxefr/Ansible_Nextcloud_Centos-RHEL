Role Name
=========

This ansible role will create deploy a nextcloud server

Requirements
------------
ansible
python
Centos8

Role Variables
--------------

mysql_root_password: Sets the password for the mysql root account
mysql_admin_password: Sets the password for the nextcloud admin account

Dependencies
------------

ansible 2.9.11
python version = 3.8.5
Centos8

Example Playbook
----------------


  - hosts: server
    gather_facts: true
    become: true
    roles:
    - nextcloud

License
-------

BSD

Author Information
------------------
Created by Derron Knox
Derron.Knox@gmail.com
linkedin.com/in/derronknox/