# Ansible Role: AWS NVMe Device Files

An [Ansible Galaxy](https://galaxy.ansible.com/) role for creating device files using AWS block device names for NVMe devices and partitions.

# Requirements

*None*

Role Variables
--------------

*None*

# Example Requirements File

```yml
- src: https://github.com/companieshouse/ansible-role-aws-nvme-device-files
  name: aws-nvme-device-files
```


# Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yml
    - hosts: servers
      roles:
        - aws-nvme-device-files
```

# License

MIT
