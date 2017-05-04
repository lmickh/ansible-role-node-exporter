Role Name
=========

Creates a systemd service to run the Prometheus node-exporter as a Docker container.

Requirements
------------

Docker, docker-py, and  systemd

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

TODO: Add Docker deps

Example Playbook
----------------

    - name: Prometheus node-exporter
      hosts: monitor
      become: yes
      roles:
        - { role: lmickh.node-exporter }
      tags:
        - node-exporter

License
-------

MIT
