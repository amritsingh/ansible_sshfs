# ansible_sshfs
Ansible role for mounting SSHFS

Role Variables
--------------

Following variables need to be defined:

- remote_media_directory: Directory where disk is mounted on the remote machine
- ssh_username
- ssh_server: IP of the remote machine
- ssh_media_directory: Directory where SSHFS will be mounted
- server_loc: eg. <user>@<ip>:<"directory where disk is mounted on the remote machine">

Note: There are no default values for the above mentioned variables.

Dependencies
------------

This package has no dependencies on modules not included with Ansible by default.

License
-------

Apache

Author Information
------------------

Created by Amrit Singh
https://www.twitter.com/_amrit_
