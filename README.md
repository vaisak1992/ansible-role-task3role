Ansible Role: task3role
=========

Configure and launch a wordpress site using ansible roles in an ubuntu server.

Requirements
------------

None

Role Variables
--------------

```bash
web_user: ubuntu
web_group: ubuntu
web_dest: '/var/www/html/task3'
www_files:
  - wordpress
```

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: mnode
      roles:
         - { role: vaisak1992.task3role, web_user: ubuntu }

License
-------

GNU GPLv3

Author Information
------------------


