# docker-compose

[![Build Status](https://travis-ci.org/m31271n/ansible-role-docker-compose.svg?branch=master)](https://travis-ci.org/m31271n/ansible-role-docker-compose)
[![Ansible Galaxy](https://img.shields.io/badge/galaxy-m31271n.docker--compose-blue.svg)](https://galaxy.ansible.com/m31271n/docker-compose)

Ansible role that installs docker-compose.

## Requirements

None.

## Role Variables

+ `docker_compose_version`: 1.14.0
+ `docker_compose_src`: `https://github.com/docker/compose/releases/download/{{ docker_compose_version }}/docker-compose-Linux-x86_64`
+ `docker_compose_dest`: `/usr/local/bin/docker-compose`

## Dependencies

None.

## Example Playbook

```
- hosts: servers
  roles:
    - role: m31271n.docker-compose
      docker_compose_version: 1.14.0
```

* * *

<p align="center">Made with ❤ by <a href="http://index.m31271n.com">m31271n</a></p>
