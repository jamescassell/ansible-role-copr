copr
====

Enable a COPR repository.

Requirements
------------

None.

Role Variables
--------------

```yaml
# name of the copr repo to enable
copr_repo: user/project

# whether the COPR repo should be enabled or disabled
copr_state: enabled
```

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
      - role: copr
        copr_repo: cyberpear/epel8

License
-------

Apache-2.0 or MIT or BSD-3-Clause

Author Information
------------------

[James Cassell](https://github.com/jamescassell)
