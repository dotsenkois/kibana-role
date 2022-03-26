kibana role
=========

Роль для установки kibana на хостах с ОС: Debian, Ubuntu, CentOS, RHEL.

Requirements
------------

Поддерживаются только ОС семейств debian и EL.

Role Variables
--------------

| Variable name | Default | Description |
|-----------------------|----------|-------------------------|
| kibana_version | "8.1.0" | Параметр, который определяет какой версии kibana будет установлен |

Example Playbook
----------------

    - hosts: all
      roles:
         - { role: kibana_role }

License
-------

BSD


