# hotspot-ansible

Installs [Hotspot](https://github.com/rthurman/hotspot)

[![Build Status](https://travis-ci.org/calvinmclean/hotspot-ansible.svg?branch=master)](https://travis-ci.org/calvinmclean/hotspot-ansible)

### Role Variables

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

| Variable                | Required | Default | Choices                   | Comments                                   |
|-------------------------|----------|---------|---------------------------|--------------------------------------------|
| VERSION                 | yes      | 4.1.0   | Any version number        | Controls the version of installed software |
| ATMOUSERNAME            | yes      |         | Username                  | The username of home directory to put files in |
