Custom Docker Image
=========

A role to build, push and deploy a custom Docker image.

Requirements
------------

- Docker

Role Variables
--------------

For all variables please see `defaults/main.yml`.

Dependencies
------------

None

Example Playbook
----------------

    ---
    - hosts: all
      roles:
        - generic_docker_image_role