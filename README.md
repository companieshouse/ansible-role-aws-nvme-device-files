# Ansible Role: AWS NVMe Device Files

An [Ansible Galaxy](https://galaxy.ansible.com/) role for creating device files using AWS block device names for NVMe devices and partitions.

## Requirements

* A Python `2.x` or `3.x` interpreter

## Role Variables

*None*

## Example Requirements File

```yml
- src: https://github.com/companieshouse/ansible-role-aws-nvme-device-files
  name: aws-nvme-device-files
  version: "n.n.n"
```

## Example Playbook

```yml
    - hosts: servers
      roles:
        - aws-nvme-device-files
```

## License

MIT
