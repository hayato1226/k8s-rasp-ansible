rasp-docker
=========

Raspberry pi に Docker CE を導入するAnsible playbook.

Requirements
------------

None.

Role Variables
--------------

ssh_port : ノード再起動確認用のssh port番号. 

Dependencies
------------

None.

Example Playbook
----------------

Playbook:

```
    - hosts: servers
      vars:
        ssh_port: 22
      roles:
         - rasp-docker
```

License
-------

BSD

Author Information
------------------

This role was created in 2018 by Hayato Yasuhisa.