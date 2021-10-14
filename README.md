# Ansible Role: Samba

[![CI](https://github.com/pmikus/ansible-role-samba/actions/workflows/CI.yml/badge.svg)](https://github.com/pmikus/ansible-role-samba/actions/workflows/CI.yml)
[![Reliability Rating](https://sonarcloud.io/api/project_badges/measure?project=pmikus_ansible-role-samba&metric=reliability_rating)](https://sonarcloud.io/dashboard?id=pmikus_ansible-role-samba)
[![Bugs](https://sonarcloud.io/api/project_badges/measure?project=pmikus_ansible-role-samba&metric=bugs)](https://sonarcloud.io/dashboard?id=pmikus_ansible-role-samba)

Installs Samba client and server.

## Requirements

Samba requires ports 137, 138, 139, 445 to be open to function properly.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    var: "value"

Brief description.


## Dependencies

None

## Example Playbook

    - hosts: localhost
      roles:
        - pmikus.samba

## License

MIT / BSD

## Author Information

This role was created by [Peter Mikus](https://www.linkedin.com/in/petermikus/).
