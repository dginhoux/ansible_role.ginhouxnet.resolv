Ansible Role : dginhoux.resolv
=========

This ansible role configure DNS resolver.
It can be used to configure both legacy `/etc/resolv.conf` or systemd resolvd


Requirements
------------

This role require a supported platform defined in `meta/main.yml`.
It will skip node with unsupported platform ; this behaviour can be bypassed by settings this variable `asserts_bypass=True`.


Role Variables
--------------

```yaml
resolv_mode: legacy
# resolv_mode: resolved


resolv_nameservers: []
resolv_search: []
```


Dependencies
------------

none


Example Playbook
----------------



License
-------

BSD


Author Information
------------------

https://github.com/dginhoux/
