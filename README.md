## phpstorm

[![CI](https://github.com/Oefenweb/ansible-phpstorm/workflows/CI/badge.svg)](https://github.com/Oefenweb/ansible-phpstorm/actions?query=workflow%3ACI)
[![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-phpstorm-blue.svg)](https://galaxy.ansible.com/Oefenweb/phpstorm)

Set up [PhpStorm](https://www.jetbrains.com/phpstorm/).

#### Requirements

None

#### Variables

* `phpstorm_version` [default: `2019.1`]: [Version](https://www.jetbrains.com/phpstorm/download/index.html#section=linux) to install
* `phpstorm_install_prefix` [default: `/opt`]: Install prefix

## Dependencies

None

#### Example

```yaml
---
- hosts: all
  roles:
    - phpstorm
```

#### License

MIT

#### Author Information

Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-phpstorm/issues)!
