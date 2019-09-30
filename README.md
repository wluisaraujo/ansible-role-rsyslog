[![Ansible Galaxy](https://img.shields.io/badge/Ansible%20Galaxy-Rsyslog-blue.svg)](https://galaxy.ansible.com/wluisaraujo/iac-ansible-rsyslog-client) [![Build Status](https://travis-ci.org/wluisaraujo/ansible-role-rsyslog.svg?branch=master)](https://travis-ci.org/wluisaraujo/ansible-role-rsyslog)
---
# IaC: with [Ansible](https://www.ansible.com) role to install and configure [Rsyslog Client](https://www.rsyslog.com/)
------------

Description
------------

 *

Requirements
------------

 *

Installation
------------

```console
vagrant@localhost:~$ ansible-galaxy install wluisaraujo.rsyslog
vagrant@localhost:~$ ansible-galaxy install -r wluisaraujo.rsyslog/requirements.txt
```

Role Variables
--------------

[defaults/main.yml](defaults/main.yml)

Dependencies
------------

* None

Example Playbook
----------------
```yaml
---
- hosts: localhost
  vars:
    - name: value
  roles:
    - rsyslog
...
```

----------------
[![Licence](https://img.shields.io/badge/License-GPL%20v3-red.svg)](https://www.gnu.org/licenses/gpl-3.0.pt-br.html)
