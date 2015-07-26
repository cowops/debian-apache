Debian-Apache
=============

The Apache HTTP Server Project is an effort to develop and maintain an open-source HTTP server for modern operating systems including UNIX and Windows NT. The goal of this project is to provide a secure, efficient and extensible server that provides HTTP services in sync with the current HTTP standards.

Requirements
------------

This role requires a debian compliant system such as ubuntu.

Role Variables
--------------

No variables

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: loranger.debian-apache }

Tasks
-----

  - Install [apache](http://httpd.apache.org/) (mpm-prefork version)
  - Enable expires, ssl and rewrite modules

License
-------

BSD