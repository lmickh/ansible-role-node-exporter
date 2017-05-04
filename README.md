Role Name
=========

Creates a systemd service to run the Prometheus node-exporter as a Docker container.

Requirements
------------

Docker, docker-py, and  systemd

Role Variables
--------------

See defaults/main.yml

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
