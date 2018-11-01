uclalib_role_memcached
=========

Ansible role that installs memcached on RHEL6/7 & CentOS 6/7 systems.

Requirements
------------

RedHat 6/7 or CentOS 6/7 installed

Role Variables
--------------

Variables used when registering subscriptions via activation key:
* `memcached_pkg` - default memcached package name for RHEL based system used is memcached

* `memcached_port` - port that memcached runs on

* `memcached_listen` - IP that memcached listens on

* `memcached_mem_limit` - sets max memory limit for caching objects in memcached

* `memcached_max_conn` - sets max connections allowed for memcached

* `memcached_log_file` - sets location of log files. default verbosity is -vv

* `memcached_conf` - default value for this role is in /etc/sysconfig/memcached

* `memcached_user` - default user is memcached


Dependencies
------------

None.

Example Playbook
----------------
Please look in the tests directory for a sample playbook to run.