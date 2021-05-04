Ansible role for unsubscribe-rhn-shutdown
==================================

Sets up systemd unit file to unsubscribe from RHN on shutdown

[![GitHub Actions](https://github.com/mongodb-ansible-roles/ansible-role-unsubscribe-rhn-shutdown/workflows/Molecule%20Test/badge.svg)](https://github.com/mongodb-ansible-roles/ansible-role-unsubscribe-rhn-shutdown/actions?query=workflow%3A%22Molecule+Test%22)
[![GitHub Actions](https://github.com/mongodb-ansible-roles/ansible-role-unsubscribe-rhn-shutdown/workflows/Release/badge.svg)](https://github.com/mongodb-ansible-roles/ansible-role-unsubscribe-rhn-shutdown/actions?query=workflow%3A%22Release%22)

Explanation
-----------

This will set up an systemd unit file that will run on halting (instance shutdown, termination and restart)
The systemd unit calls `/usr/sbin/subscription-manager unregister` to unsubscribe a box from RHN before termination

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
