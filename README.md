[![Build Status](https://travis-ci.org/wluisaraujo/iac-ansible-rsyslog-client.svg?branch=master)](https://travis-ci.org/wluisaraujo/iac-ansible-rsyslog-client)
---
# IaC: with [Ansible](https://www.ansible.com) role to install and configure [Rsyslog Client](https://www.rsyslog.com/)
------------

Description
------------

 *

Requirements
------------

 *

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
    - iac-ansible-rsyslog-client
...    
```

----------------
[![Licence](https://img.shields.io/badge/License-GPL%20v3-red.svg)](https://www.gnu.org/licenses/gpl-3.0.pt-br.html)
