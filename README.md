[![Build Status - Master](https://travis-ci.org/juju4/ansible-wef.svg?branch=master)](https://travis-ci.org/juju4/ansible-wef)
[![Build Status - Devel](https://travis-ci.org/juju4/ansible-wef.svg?branch=devel)](https://travis-ci.org/juju4/ansible-wef/branches)
# DetectionLab Windows WEF ansible role

Setup a Windows WEF server for [DetectionLab](https://github.com/clong/DetectionLab)

WARNING! Work in progress.

## Requirements & Dependencies

### Ansible

Tested with Ansible 2.9

### Operating systems

Targeted for Windows 2016.

### Dependencies

```
$ ansible-galaxy install -r requirements.yml
```

[TODO]

## Example Playbook

Including an example of how to use your role (for instance, with variables
passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: juju4.wef, x: 42 }

You can test with vagrant
```
$ vagrant plugin install vagrant-reload
$ cd test/vagrant
$ vagrant up
$ vagrant provision
$ vagrant ssh
```
Please note that if you run multiple windows VM concurrently, winrm port might change and need to be set manually.

## Continuous integration

This role is tested in Appveyor.

## License

BSD 2-clause
