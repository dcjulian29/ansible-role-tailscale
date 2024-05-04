# Ansible Role: tailscale

[![Lint](https://github.com/dcjulian29/ansible-role-tailscale/actions/workflows/lint.yml/badge.svg)](https://github.com/dcjulian29/ansible-role-tailscale/actions/workflows/lint.yml) [![GitHub Issues](https://img.shields.io/github/issues-raw/dcjulian29/ansible-role-tailscale.svg)](https://github.com/dcjulian29/ansible-role-tailscale/issues)

This an Ansible role to install and enable a Tailscale node.

## Requirements

- Active Internet Connection.

## Installation

To use, use `requirements.yml` with the following git source:

```yaml
---
roles:
- name: dcjulian29.tailscale
  src: https://github.com/dcjulian29/ansible-role-tailscale.git
  ```

Then download it with `ansible-galaxy`:

```shell
ansible-galaxy install -r requirements.yml
```

## Dependencies

- None
