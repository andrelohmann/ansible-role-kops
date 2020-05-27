kops
====

[![Build Status](https://travis-ci.org/andrelohmann/ansible-role-kops.svg?branch=master)](https://travis-ci.org/andrelohmann/ansible-role-kops)

Use this role to install kops.

Requirements
------------

This role requires ubuntu.

Role Variables
--------------

    kops_version: 1.16.2 # defaults to 'latest'

Example Playbook
----------------

    - hosts: kops
      roles:
         - andrelohmann.kops

License
-------

MIT

Author Information
------------------

https://github.com/andrelohmann
