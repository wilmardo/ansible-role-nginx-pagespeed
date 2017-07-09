Optimized Nginx [![Build Status](https://travis-ci.org/wilmardo/ansible-nginx.svg?branch=master)](https://travis-ci.org/wilmardo/ansible-nginx)
=========

Nginx server compiled from source with the pagespeed module.

Requirements
------------

None

Role Variables
--------------

The vars underneath can be set to your liking
| Variable name           | Default value         | Description         |
| ----------------------- | --------------------- | ------------------- |
| plexpy_install          | yes                   | To install PlexPy
| plexpy_user             | plexpy                | The user PlexyPy runs as
| plexpy_group            | plexpy                | The group PlexPy runs as
| plexpy_install_location | /opt/plexpy/          | PlexPy install location
| plexpy_config_location: | /etc/plexpyconfig.ini | PlexPy config file (recommended is to put it somewhere in /etc)
| plexpy_data_location:   | /opt/plexpy/data      | PlexPy datadir (recommended is to NOT put it in your PlexPy exec dir)

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: wilmardo.nginx, x: 42 }

License
-------

BSD

Author Information
------------------

Wilmar den Ouden

https://wilmardenouden.nl