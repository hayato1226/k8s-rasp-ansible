rasp-docker
=========

Raspberry pi に docker ce を導入するAnsible playbook.

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

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

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