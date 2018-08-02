[![Build Status](https://travis-ci.org/oasis-roles/rhv_storage_domains.svg?branch=master)](https://travis-ci.org/oasis-roles/rhv_storage_domains)

ROLE NAME
===========

Basic description for rhv_storage_domains

Requirements
------------

Ansible 2.4 or higher

Red Hat Enterprise Linux 7 or equivalent

Valid Red Hat Subscriptions

Role Variables
--------------

Currently the following variables are supported:

### General

* `rhv_storage_domains_var_name` - var\_name description

Dependencies
------------

None

Example Playbook
----------------

```yaml
- hosts: rhv_storage_domains-servers
  roles:
    - role: oasis-roles.rhv_storage_domains
```

License
-------

GPLv3

Author Information
------------------

Author Name <authoremail@domain.net>