NTP
====

Install and configure NTP Server.

Requirements
-------------

This role requires ansible 2.0 or higher.

Role Variables
--------------

The variables that can be passed to this role and a brief description about them are as follows:

```
---
ntp_server:
  - ntp.exact-time.org
  - time.cloudflare.com
  - ntp1.itcompliance.dk
  - ntp.ea1145.net

```


Dependencies
------------

Example Playbook
----------------

```
---
- hosts: all
  become: True
  roles:
    - { role: 1mr.ntp, tags: ntp }

```

License
-------

MIT

Author Information
------------------

Created by Stas Stavnichuk 
