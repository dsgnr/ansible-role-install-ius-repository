# Ansible Role: Install IUS Repository

[![Build Status](https://travis-ci.org/dsgnr/ansible-role-install-ius-repository.svg?branch=master)](https://travis-ci.org/dsgnr/ansible-role-install-ius-repository)
[![Build Status](https://jenkins.handsoff.cloud/buildStatus/icon?job=ansible-role-install-ius-repository%2Fmaster)](https://jenkins.handsoff.cloud/job/ansible-role-install-ius-repository/job/master/)

This role installs the IUS repository on RedHat and CentOS distros

## Requirements

None.

## Role Variables

None.

## Dependencies

None.

## Example Playbook

    - hosts: all
      become: true

      roles:
        - install-ius

## License

GNUv3

## Author Information

This role was created by [Dan Hand](https://danielhand.io).
