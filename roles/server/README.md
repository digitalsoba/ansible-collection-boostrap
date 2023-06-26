Role Name
=========

Bootstraps a server with a user, grabs public ssh keys from their public github account, disables ssh root/password login, and installs a few packages.

Requirements
------------

Only works for debian based distro. 

Role Variables
--------------

- user
- github_keys
- common_packges
- apt_packages
- sudogroup

Dependencies
------------

N/A

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: digitalsoba.bootstrap.server, user: foobar }

License
-------

BSD

Author Information
------------------

N/A
