[![Build Status](https://travis-ci.org/lifeofguenter/ansible-role-couchpotato.svg?branch=master)](https://travis-ci.org/lifeofguenter/ansible-role-couchpotato)

# Ansible Role: CouchPotato

An Ansible role that installs CouchPotato on Debian like systems.

## Requirements

none

## Role Variables

```yaml
couchpotato_user: couchpotato

couchpotato_data_dir: ''
```

## Dependencies

none

## Example Playbook

    - hosts: media-center
      roles:
        - { role: lifeofguenter.couchpotato }

## License

MIT
