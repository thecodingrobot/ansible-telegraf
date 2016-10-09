Ansible role: Telegraf
=========

Installs [Telegraf](https://www.influxdata.com/time-series-platform/telegraf/) on CentOS/RedHat Linux.

Requirements
------------

None

Role Variables
--------------

- telegraf_influxdb_url
- telegraf_influxdb_dbname
- telegraf_influxdb_username
- telegraf_influxdb_password


Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - thecodingrobot.telegraf

License
-------

BSD