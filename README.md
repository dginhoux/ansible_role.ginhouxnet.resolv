ginhouxnet.resolv
=========

This ansible role configure DNS resolver.
It can be used to configure both legacy /etc/resolv.conf or systemd resolvd


Requirements
------------

This role is built to only run on platforms defined in `meta/main.yml`


Role Variables
--------------

It's just a simple list like : 

```
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
