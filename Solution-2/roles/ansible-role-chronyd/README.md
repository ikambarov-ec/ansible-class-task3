Ansible-Role-Chronyd
=========
This is a simple role which updates /etc/chrony.conf

Requirements
------------
None

Role Variables
--------------
ntp_servers:
- 'pool.ntp.org'
- 'time-a-g.nist.gov'   

Dependencies
------------
None

Example Playbook
----------------
  roles:
    - role: ansible-role-chornyd
      vars:
      ntp_servers:
      - 'time1.google.com' 
      - 'time2.google.com'          

License
-------
MIT

Author Information
------------------
Islam Kambarov

