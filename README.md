## Install Go lang

This role installs [Golang](https://golang.org/) from a binary package.

[![Build Status](https://travis-ci.org/gtrafimenkov/ansible-role-golang.svg)](http://travis-ci.org/gtrafimenkov/ansible-role-golang)
[![Ansible Role](https://img.shields.io/badge/role-gtrafimenkov.golang-blue.svg?maxAge=2592000)](https://galaxy.ansible.com/gtrafimenkov/golang)

### Usage

By default the latest stable version is installed.

You can specify another version using variable `golang_version`.  For example:

```
---
- hosts:
    - testhost
  become: yes
  vars:
    golang_version: 1.4.3
  roles:
    - gtrafimenkov.golang
```

### Supported Version

- 1.6.3
- 1.5.4
- 1.4.3

### Supported Platforms

- Linux x64
- Linux i386

### License

MIT
