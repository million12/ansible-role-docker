Ansible Role: Install Docker (stable)
=========
[![Travis](https://img.shields.io/travis/million12/ansible-role-docker.svg)](https://travis-ci.org/million12/ansible-role-docker)
[![GitHub Open Issues](https://img.shields.io/github/issues/million12/ansible-role-docker.svg)](https://github.com/million12/ansible-role-docker/issues)
[![GitHub Stars](https://img.shields.io/github/stars/million12/ansible-role-docker.svg)](https://github.com/million12/ansible-role-docker)
[![GitHub Forks](https://img.shields.io/github/forks/million12/ansible-role-docker.svg)](https://github.com/million12/ansible-role-docker)
[![GitHub release](https://img.shields.io/github/release/million12/ansible-role-docker.svg)](https://github.com/million12/ansible-role-docker)
[![license](https://img.shields.io/github/license/million12/ansible-role-docker.svg)](https://github.com/million12/ansible-role-docker/blob/master/LICENSE)

---

This Role is installing Docker latest stable version

Requirements
------------

Tested on CentOS 7 but should work on RHEL equivalents.

Role Variables
--------------

N/A

Dependencies
------------

N/A

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: million12.docker, tags: ['install'] }

License
-------

MIT

Author Information
------------------

Author: Przemyslaw Ozgo (<przemek@m12.io>)

---
**Sponsored by [Prototype Brewery](http://prototypebrewery.io/)** - the new prototyping tool for building highly-interactive prototypes of your website or web app. Built on top of [Neos CMS](https://www.neos.io/) and [Zurb Foundation](http://foundation.zurb.com/) framework.
