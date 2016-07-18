Role Name
=========

This role install cron-apt app and setup cron job for install security patches

Role Variables
--------------
Varible in this role mention in group_vars.you have to mention cron job time,apt mirror and notification and debug config for cron-apt


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```sh
- hosts: webservers
  remote_user: kasun
  sudo: yes
  vars_files:
    - group_vars/cron-apt-vars

  roles:
    - cron-apt
```

Author Information
------------------
Kasun Madura Rathnayaka
mail:kasummaduraeng@gmail.com
