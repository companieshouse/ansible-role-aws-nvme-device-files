# Ansible Role: AWS NVMe Device Files

An [Ansible Galaxy](https://galaxy.ansible.com/) role for creating device files using AWS block device names for NVMe devices and partitions.

## Requirements

*None*

## Role Variables

*None*

## Example Requirements File

```yml
- src: https://github.com/companieshouse/ansible-role-aws-nvme-device-files
  name: aws-nvme-device-files
```


## Example Playbook

```yml
    - hosts: servers
      roles:
        - aws-nvme-device-files
```

## License

MIT
