Ansible Role: Rsnapshot
=========

An Ansible role for installing and configuring rsnapshot for automated backups.

Requirements
------------

None.

Role Variables
--------------

The available variables, along with their default values, can be found in the defaults/main.yml file.

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
