# Ansible Role: Install Java

[![Build Status](https://travis-ci.org/tschifftner/ansible-role-java.svg)](https://travis-ci.org/tschifftner/ansible-role-java)

Installs java on Debian/Ubuntu linux servers.

## Requirements

ansible 1.8+

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

```
java_packages:
  - openjdk-7-jdk
```

## Dependencies

None.

## Installation

```
$ ansible-galaxy install tschifftner.java
```

## Example Playbook

    - hosts: server
      roles:
        - { role: tschifftner.java }

Ansible          | Debian Jessie    | Ubuntu 14.04    | Ubuntu 12.04
:--------------: | :--------------: | :-------------: | :-------------: 
1.8              | Yes              | Yes             | Yes
1.9              | Yes              | Yes             | Yes
2.0              | Yes              | Yes             | Yes

## License

MIT / BSD

## Author Information

 - Tobias Schifftner, @tschifftner