# sbog/victoriametrics

[![Build Status](https://travis-ci.com/sorrowless/ansible_victoriametrics.svg?branch=master)](https://travis-ci.com/sorrowless/ansible_victoriametrics)
[![Ansible Role](https://img.shields.io/ansible/role/54630)](https://galaxy.ansible.com/sorrowless/victoriametrics)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/54630)](https://galaxy.ansible.com/sorrowless/victoriametrics)
[![Ansible Role](https://img.shields.io/ansible/role/d/54630)](https://galaxy.ansible.com/sorrowless/victoriametrics)
[![GitHub](https://img.shields.io/github/license/sorrowless/ansible_victoriametrics)](https://github.com/sorrowless/ansible_victoriametrics/blob/master/LICENSE)

An Ansible role which installs and configures [Victoriametrics](https://github.com/VictoriaMetrics/VictoriaMetrics)

## Requirements

Ansible 2.8+

## Role Variables

You can see all vars in `defaults/main.yml` vars file.

## Dependencies

None

## Example Playbook

```yaml
- name: Ensure victoriametrics
  hosts: victoriametricss
  remote_user: root

  roles:
    - victoriametrics
```

## License

Apache 2.0

## Author Information

This role was created by [Stan Bogatkin](https://sbog.ru).
