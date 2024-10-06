ansible-lighthouse
=========

This role install Lighthouse

Role Variables
--------------
You can change Lighthouse version

```yaml
lighthouse_version: "0.41.1"
```

Configure
--------

Refer the file templates/lighthouse.conf.j2 to change the default values for Vector.

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
