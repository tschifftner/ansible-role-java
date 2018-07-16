# Ansible Role: Install Java

[![Build Status](https://travis-ci.org/tschifftner/ansible-role-java.svg?branch=master)](https://travis-ci.org/tschifftner/ansible-role-java)

Installs java on Debian/Ubuntu linux servers.

## Requirements

None

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

```
java_version: 10
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

## Supported Java versions

**Java 10:** All supported OS

~~**Java 9:**~~ Not supported due to download problems

**Java 8:** All supported OS except for Ubuntu 18.04 (Bionic Beaver). Will be removed for Java 11.


## Supported OS

 - Debian 9 (Stretch)
 - Debian 8 (Jessie)
 - Ubuntu 18.04 (Bionic Beaver)
 - Ubuntu 16.04 (Xenial Xerus)
 
## Required ansible version

Ansible 2.5+

## License

[MIT License](http://choosealicense.com/licenses/mit/)

## Author Information

 - [Tobias Schifftner](https://twitter.com/tschifftner), [ambimax® GmbH](https://www.ambimax.de)