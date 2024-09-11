# Ansible Role: `iavf_dkms`

## Description
This role installs the `iavf` driver for Intel Ethernet Network Adapters.

## Requirements
This role requires the `dkms` package to be installed on the target system.

## Role Variables
The role has the following variables:

```yaml
iavf_dkms_version: "4.6.1"
```

## Dependencies
None

## Example Playbook
```yaml
- hosts: all
  roles:
    - iavf_dkms
```

## License
MIT

## Author Information
