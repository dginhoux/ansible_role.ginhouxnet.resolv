ginhouxnet.sysctl
=========

This ansible role configure DNS resolver.
It can be used to configure both legacy /etc/resolv.conf or systemd resolvd


Requirements
------------

This ansible role will only run on identified OS defined on meta/main.yml


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




Example Playbook
----------------



License
-------

BSD


Author Information
------------------

Dany GINHOUX
