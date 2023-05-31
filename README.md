Ansible Role: Rsnapshot
=========

An Ansible role for installing and configuring rsnapshot for automated backups.

Requirements
------------

This Ansible role has been developed and thoroughly tested with Ansible Core version 2.15.0.

This role was designed for:

- CentOS 8 Stream
- RHEL 8

Role Variables
--------------

[defaults/main.yml](defaults/main.yml).

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: all
      become: true
      vars_files:
        - group_vars/rsnapshot.yml
      roles:
        - ansible-role-rsnapshot

License
-------

MIT / BSD

🇬🇧🇭🇰 Author Information
------------------

* Author: Jody WAN
* Linkedin: https://www.linkedin.com/in/jodywan/
* Website: https://www.jodywan.com
