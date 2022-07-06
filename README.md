Ansible Role: MongoDB
=========

Эта роль установит MongoDB версии 4.4 на ОС CentOS.

Requirements
------------

None.

Role Variables
--------------

Доступные переменные перечислены ниже вместе со значениями по умолчанию в файле **defaults/main.yml**.

Dependencies
------------

Для подключения по сети необходимо открыть следующие порт в firewall:
```
port: 27017/tcp
```

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - mongodb

License
-------

BSD

Author Information
------------------

Chubik Sergey.
