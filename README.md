[![Build Status](https://travis-ci.org/tjtoml/ansible-role-nginx.svg?branch=master)](https://travis-ci.org/tjtoml/ansible-role-nginx) [![role](https://img.shields.io/badge/Galaxy-tjtoml.nginx-5bbdbf.svg)](https://galaxy.ansible.com/tjtoml/nginx/)   

tjtoml.nginx
=========

Installs nginx from the nginx official repositories found at http://nginx.org  
This role is intented as a building block - it is not designed to implement all the options available for nginx, only install it from the project repositories. 

Requirements
------------

None.

Role Variables
--------------

None. 

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: webservers
      roles:
         - { role: tjtoml.nginx }

License
-------

MIT
