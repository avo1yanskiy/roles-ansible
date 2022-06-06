Filebeat role
=========

Роль для установки Filebeat на хостах с ОС: Debian, Ubuntu, CentOS, RHEL.

Requirements
------------

Поддерживаются только ОС семейств debian и EL.

Role Variables
--------------

| Variable name | Default | Description |
|-----------------------|----------|-------------------------|
| Filebeat_version | "7.14.1" | Параметр, который определяет какой версии Filebeat будет установлен |

Example Playbook
----------------

    - hosts: all
      roles:
         - { role: filebeat_role }

License
-------

BSD

Author Information
------------------

Aleksandr Volyanskiy