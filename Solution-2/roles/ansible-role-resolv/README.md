Ansible-Role-Resolv
=========
This is a simple role which updates /etc/resolv.conf

Requirements
------------
None

Role Variables
--------------
nameservers:
- '103.86.96.100'
- '103.86.99.100'

Dependencies
------------
None

Example Playbook
----------------
  roles:
    - role: ansible-role-hostname
      vars:
        nameservers:
        - '8.8.8.8'
        - '8.8.4.4'

License
-------
MIT

Author Information
------------------
Islam Kambarov

