Role: cns.aws-keypair-credstash
========

Ansible role to generate an EC2 keypair and store it using credstash

Requirements
------------

* [credstash](https://github.com/fugue/credstash)

Role Variables
--------------

See task files for variables.

Install
-------

Add the following line to your `requirements.yml`:

```yml
- src: https://github.com/cnstechnicalgroup/role-aws-keypair-credstash.git
  name: cns.aws-keypair-credstash
```

Dependencies
------------

This package has no dependencies.

License
-------

GPLv2

Author Information
------------------

Sam Morrison

Examples
--------

```yaml
---
- name: aws-keypair-credstash example
  hosts: all
  roles:
    - cns.aws-keypair-credstash
```
