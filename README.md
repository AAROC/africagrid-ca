[![Build Status](https://travis-ci.org/AAROC/africagrid-ca.svg?branch=master)](https://travis-ci.org/AAROC/africagrid-ca)
AfricaGrid CA
=========

This deploys the web site for the AfricaGrid CA (online)

Requirements
------------

none

Role Variables
--------------

none

Dependencies
------------

none

Example Playbook
----------------

    - hosts: online-ca
      roles:
         - { role: aaroc.africagrid-ca, become: true }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
