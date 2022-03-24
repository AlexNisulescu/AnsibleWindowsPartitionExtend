win_part_extend
=========

This role is used to extend an existing windows partition.

Role Variables
--------------

  - vcenter_hostname
  - vcenter_username
  - vcenter_username
  - datacenter
  - folder
  - vm_name
  - vm_username
  - vm_password
  - partitionLetter
  - diskNumber
  - formatType

Dependencies
------------

 - community.vmware

Example Playbook
----------------

    - hosts: localhost
      roles:
         - win_part_mount

Contributors
----------------

    Creator: Alexandru Nișulescu
    Contact: alex.nisulescu1998@gmail.com
    Linkedin: https://www.linkedin.com/in/alex-nisulescu-45822b178/
