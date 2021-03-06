Tower Installation
==================
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/bd70ba994a2644ae93316bdfc4fbc685)](https://www.codacy.com/app/gahancorpcfo/tower?utm_source=github.com&utm_medium=referral&utm_content=gahan-corporation/tower&utm_campaign=badger)
[![Build Status](https://travis-ci.org/gahan-corporation/tower.svg?branch=master)](https://travis-ci.org/gahan-corporation/tower)

Installs the latest version of Ansible Tower onto an Ubuntu 16.04 target.

[Full of Helpful Advice](https://stackoverflow.com/questions/1885251/how-do-i-tell-pylint-its-a-variable-not-a-constant-to-stop-message-c0103)

Requirements
------------

The `molecule` Python library is required for testing.

Role Variables
--------------

None.

Dependencies
------------

```yaml
role: gahan-corporation.postgresql
```

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
     - { role: gahan-corporation.tower }
```

License
-------

GPL-3.0

Author Information
------------------

Authored by A. H. Laughlin for the [Gahan Corporation](https://gahan-corporation.com).
