TORRENT Ansible role
====================

Role to manage TORRENT.

Requirements
------------

No requirements

Role Variables
--------------

`torrent__install:` For install only (default: False)
`torrent__configure:` For configuration  (default: False)


Dependencies
------------

None

Example Playbooks
-----------------

Play with:

```
- hosts: all
  name: Setup Transmission server
  roles:
    - role: torrent
```

With vars like:

```

```

License
-------

GPLv3

Author Information
------------------

François TOURDE

