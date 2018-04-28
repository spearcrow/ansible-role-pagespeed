# Ansible Role: nginx-pagespeed

Installs Google Pagespeed Dynamic Module for Nginx.

## Requirements

nginx 1.11.5 (minimum)

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    google_pagespeed_version: 1.13.35.2-stable

## Dependencies

None.

## Example Playbook

    - hosts: servers
      roles:
        - { role: miguelenes.nginx-pagespeed }

## License

MIT / BSD

## Author Information

This role was created in 2018 by [Miguel Enes](https://galaxy.ansible.com/miguelenes).
