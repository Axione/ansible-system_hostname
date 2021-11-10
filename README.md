# ansible-system_hostname

## Description

[![Galaxy Role](https://img.shields.io/badge/galaxy-system_hostname-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/system_hostname)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-system_hostname.svg)](https://github.com/lotusnoir/ansible-system_hostname/releases/latest)
![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-system_hostname?color=orange&style=flat)
[![downloads](https://img.shields.io/ansible/role/d/56111)](https://galaxy.ansible.com/lotusnoir/system_hostname)
![Ansible Quality Score](https://img.shields.io/ansible/quality/56111)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)


Configure hostname and /etc/hosts using ansible.

## Requirements

none

## Role variables

| Name                     | Default Value      | Description                        |
| ------------------------ | ------------------ | -----------------------------------|
|hostname_value            | inventory_hostname | Name to be set for vm|
|hostname_hosts_file       | /etc/hosts         | hosts file path |
|hostname_extra_static     | []                 | extra static local dns |
|hostname_restart_services | []                 | services to be restarted to take the new name in their config|

## Examples

        ---
        - hosts: system_hostname
          become: yes
          become_method: sudo
          gather_facts: yes
          roles:
            - role: ansible-system_hostname
          environment:
            http_proxy: "{{ http_proxy }}"
            https_proxy: "{{ https_proxy }}"
            no_proxy: "{{ no_proxy }}

## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

