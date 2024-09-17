# Ansible Role: GVisor
Install and configure GVisor for Ubuntu and CentOS hosts

>> Test

## Requirements
None

## Role Variables

## Dependencies
```
roles:
  - geerlingguy.docker
  - geerlingguy.containerd
```

## Example Playbook (using default package)
```
- hosts: servers
  roles:
  - role: grababyte.gvisor
    become: yes
```

## License
MIT / BSD

## Author Information
This role was created in 2024 by GrabAByte
