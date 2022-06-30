# Ansible Role: git

Ansible role that installs [git](https://git-scm.com)

## Requirements

None.

## Role Variables

Available variables are listed below (see `defaults/main.yml`):

- `git_packages`: List of packages necessary to install git.

## Use with Ansible


```yaml
- hosts: all
  become: true

  roles:
    - role: git
```

## Dependencies

None.

## Author Information

This role was created in 2022 by Tiago Martins.
