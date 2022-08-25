# Ansible Role : add_rm_pkgs

[![CI](https://github.com/glillico/ansible-role-add_rm_pkgs/workflows/CI/badge.svg)](https://github.com/glillico/ansible-role-add_rm_pkgs/actions?query=workflow%3ACI)

Adds or removes the defined list of packages.

## Requirements

None.

## Role Variables

### defaults/main.yml

|Variable|Description|
|---|:---|
|irp_pkg_name|Defines the package name that will get installed or removed.|
|irp_pkg_state|Defines whether the packge should be `present` or `absent`.|

## Dependencies

None.

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      vars_files:
        - vars/main.yml
      roles:
        - glillico.add_rm_pkgs

## License

MIT

## Author Information

Created in 2022 by Graham Lillico.
