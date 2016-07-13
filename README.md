# Ansible Role: Install Java

[![Build Status](https://travis-ci.org/tschifftner/ansible-role-java.svg)](https://travis-ci.org/tschifftner/ansible-role-java)

Installs java on Debian/Ubuntu linux servers.

## Requirements

None

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
2.1              | Yes              | Yes             | Yes

## License

MIT / BSD

## Author Information

 - [Tobias Schifftner](https://twitter.com/tschifftner), [ambimax® GmbH](https://www.ambimax.de)