Role Name
=========

x11vnc is a remote control software package which allows you to share mouse, keyboard and screen across networks. 

Requirements
------------

- Ansible control server
- Ubuntu
- XFCE 

Role Variables
--------------

vnc_pass


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: pb-ubt-thin
      
      vars:
         vnc_pass: Welcome123 

      roles:
         - app-x11vnc-server

License
-------

GNU GPLv3 x11vnc is a remote control software package which allows you to share mouse, keyboard and screen across networks.

Author Information
------------------

www.bitfinity.nl
