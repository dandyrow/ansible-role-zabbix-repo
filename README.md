**[Depricated]** Ansible Role - Zabbix Repo [![CI](https://github.com/dandyrow/ansible-role-zabbix-repo/actions/workflows/CI.yml/badge.svg)](https://github.com/dandyrow/ansible-role-zabbix-repo/actions/workflows/CI.yml)
=========
**This role has now been depricated and replaced by the zabbix agent role and in the future a zabbix proxy and server role.**

An Ansible role which sets up the Zabbix repository on Linux hosts.

Role Variables
--------------

`zbx_version` - Sets the Zabbix version of to install the corresponding repository.

Supported Platforms
-------------------

- Ubuntu:
  - 22.04 Jammy
  - 20.04 Focal

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
  - hosts: servers
    roles:
      - role: dandyrow.zabbix_repo
        vars:
          - zbx_version: 6.2
```

License
-------

GPL-3.0-only

Author Information
------------------

This role was created in 2022 by Daniel Lowry as part of a wider personal infrastructure as code project.
