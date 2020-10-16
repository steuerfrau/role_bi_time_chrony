role_bi_time_chrony
=========

Setup ntp client using chrony.

Requirements
------------

n.a.

Role Variables
--------------

A defaul set of timeservers is configured in ./defaults/main.yml and may be overwritten.
```
# defaults file for role_bi_time_chrony/
role_bi_time_chrony_timeservers:
  - 0.de.pool.ntp.org
  - 1.de.pool.ntp.org
  - 2.de.pool.ntp.org
  - 3.de.pool.ntp.org
```
Dependencies
------------

n.a.

Example Playbook
----------------

n.a.

License
-------

GNU Public License v3.0

Author Information
------------------

Melanie Desaive, m.desaive@mailbox.org
