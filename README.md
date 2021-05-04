Ansible role for unsubscribe-rhn-shutdown
==================================

Sets up systemd unit file to unsubscribe from RHN on shutdown

[![GitHub Actions](https://github.com/mongodb-ansible-roles/ansible-role-unsubscribe-rhn-shutdown/workflows/Molecule%20Test/badge.svg)](https://github.com/mongodb-ansible-roles/ansible-role-unsubscribe-rhn-shutdown/actions?query=workflow%3A%22Molecule+Test%22)
[![GitHub Actions](https://github.com/mongodb-ansible-roles/ansible-role-unsubscribe-rhn-shutdown/workflows/Release/badge.svg)](https://github.com/mongodb-ansible-roles/ansible-role-unsubscribe-rhn-shutdown/actions?query=workflow%3A%22Release%22)

Requirements
------------

None

Role Variables
--------------

| Name | Description | Type | Default | Required |
|------|-------------|:----:|:-------:|:--------:|
| name | desc | type | default | required |

Dependencies
------------

None

Example Playbook
----------------

```yaml
- hosts: all
  roles:
    - role: ansible-role-unsubscribe-rhn-shutdown
```

License
-------

[Apache License](LICENSE)
