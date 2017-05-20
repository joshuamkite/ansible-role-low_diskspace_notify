joshuamkite.low_diskspace_notify
=========

This script checks the free disk space on local '/' partition. It presumes this is the default lvm volume group '*root'. It will show a desktop notification to any graphically logged in loacl user  for 30 seconds when the disk usage is greater than the minor warning percentage (default: 80% full) in shell script. If greater than the major warning percentage (default: 90% full), it will show a notification for 5 minutes. These values may be changed in the shellscript 'checklowdisk'

Requirements
------------

The script installed by this role is targetted at Desktop use. It anticipates an lvm system root.

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

---
    - hosts: workstations
    
      roles:
         - joshuamkite.low_diskspace_notify
         
License
-------

GPLv3

Author Information
------------------

joshuamkite@gmail.com
