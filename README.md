ansible-lighthouse
=========

This role install Lighthouse

Role Variables
--------------

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Configure
--------

Refer the file templates/lighthouse.toml.j2 to change the default values for Lighthouse.

Dependencies
------------

Role 
  - git
  - nginx

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:
```yaml
  - hosts: lighthouse_host 
    roles:
      - { role: lighthouse }
```

License
-------

MIT

Author Information
------------------

Boris
