# ansible-role-haproxy

Ansible role to install and configure HaProxy for heavy traffic websites.

## Requirements

* Ansible version >= 2.3.*

## Role Variables

You can override all the variables in `defaults/main.yml`.

## Example Playbook

    - hosts: servers
      roles:
         - { role: monsieurbiz.haproxy }

## License

MIT

## Authors

* Michaël Thieulin - [@michaelthieulin](https://twitter.com/michaelthieulin)
