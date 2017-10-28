Role Name
=========

ansible-gitlab

Requirements
------------

None

Role Variables
--------------

```yaml
enable_postfix: Install postfix for email notifications

gitlab_external_url: External URL to use for gitlab web console
```

Dependencies
------------

None

Example Playbook
----------------
```yaml
- name: Install Gitlab
  hosts: gitlab
  become: True
  roles:
    - { role: ansible-gitlab }
```
License
-------

GPLv3

Author Information
------------------

Brad Searle

