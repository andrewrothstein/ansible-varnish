andrewrothstein.varnish
=========
![Build Status](https://github.com/andrewrothstein/ansible-varnish/actions/workflows/build.yml/badge.svg)

Installs [Varnish](https://varnish-cache.org) from OS packages.

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - andrewrothstein.varnish
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
