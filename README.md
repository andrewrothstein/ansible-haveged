andrewrothstein.haveged
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-haveged.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-haveged)

Installs [haveged](https://www.issihosts.com/haveged/).

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
    - andrewrothstein.haveged
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
