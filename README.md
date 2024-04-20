![Ansible Lint](https://github.com/johanneskastl/ansible-role-service_to_save_list_of_installed_rpms/workflows/Ansible%20Lint/badge.svg)

# service_to_save_list_of_installed_rpms

Systemd service to save a list of all installed RPM packages on boot or shutdown

## Requirements

None.

## Role Variables

- `rpm_backup_directory` (String): Path to the directory where the files should
  be saved (default: `/opt/RPMs_installed/`)

## Dependencies

None

## Example Playbook

```yaml
- hosts: servers
  roles:
    - role: 'johanneskastl.service_to_save_list_of_installed_rpms'
```

## License

BSD-3-Clause

## Author Information

I am Johannes Kastl, reachable via git@johannes-kastl.de
