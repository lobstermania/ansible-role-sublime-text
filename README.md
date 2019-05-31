Ansible role to install Sublime Text
=========

https://www.sublimetext.com/

Supports:
  - RHEL based distros (CentOS, Fedora, RedHat)
  - Deb based distros (Ubuntu, Debian)

Tested against the following:
  - ubuntu
  - fedora

Role Variables
--------------

- sublime_text_channel

Example Playbook
----------------


    - hosts: desktops
      roles:
         - { role: ansible-role-sublime-text }

License
-------

BSD

