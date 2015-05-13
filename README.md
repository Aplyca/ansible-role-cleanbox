# Ansible Role: cleanbox

[![Build Status](https://travis-ci.org/Aplyca/ansible-role-cleanbox.svg?branch=master)](https://travis-ci.org/Aplyca/ansible-role-cleanbox)
[![Circle CI](https://circleci.com/gh/Aplyca/ansible-role-cleanbox.svg?style=svg)](https://circleci.com/gh/Aplyca/ansible-role-cleanbox)

Ansible Role clean up a Vagrant box in order to be packed.


## Requirements

Use hash behavior for variables in ansible.cfg
See example: https://github.com/Aplyca/ansible-role-cleanbox/blob/master/tests/ansible.cfg
See official docs: http://docs.ansible.com/intro_configuration.html#hash-behaviour

## Installation

Using ansible galaxy:
```bash
ansible-galaxy install mauricios.cleanbox
```
You can add this role as a dependency for other roles, add the role to the meta/main.yml file of your own role:
```yaml
dependencies:
  - { role: mauricios.cleanbox }
```

## Role Variables

See default variables: https://github.com/Aplyca/ansible-role-cleanbox/blob/master/defaults/main.yml

## Dependencies

None.

## Testing

Use Vagrant to test the role:

```bash
cd tests;
vagrant up;
```

## License

MIT / BSD

## Author Information

Mauricio Sánchez from Aplyca SAS (http://www.aplyca.com)
