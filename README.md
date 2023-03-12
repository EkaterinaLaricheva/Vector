Vector role
=========

Role describes installation Vector

Requirements
------------

Prerequisites without features

Role Variables
--------------

Default vars:
vector_version: "0.21.0"

Dependencies
------------

Other used rollers:
- clickhouse-role
- lighthouse-role

Example Playbook
----------------
- name: Install Vector
  hosts: vector
  roles:
    - vector


