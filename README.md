Node Version Manager
====================

Use this role to setup [NVM](https://github.com/creationix/nvm)(Node Version Manager) and NodeJS.

Role Variables
--------------

Check [./defaults/main.yml](./defaults/main.yml) for default values for Ansible variables.

Example Playbook
----------------

Playbook to setup NVM might look like:

    - name: Setup NVM
      hosts: all
          nvm_node_version: "v6.0.0"
      roles:
        - role: nvm

License
-------

This project is released under the Apache 2 license. Read the [LICENSE.txt](./LICENSE.txt) file for more details.

Authors
-------

Update by [Ona Engineering](https://ona.io)