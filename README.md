ansible-role-find-server
========================

Installs [find](https://www.internalpositioning.com/) framework for internal navigation and discovery server component and `svm` dependency on ARM and x86_64 systems.

Requirements
------------

None

Role Variables
--------------

	find_version: 2.3

Find Version to deploy.

	find_user: find

User to run `find` service with.

	find_home: /opt/find

Install and working directory for find.

	find_log_directory: /var/log/find

Log directory for find.

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: knowhy.find-server }

License
-------

GNU AGPLv3

Author Information
------------------

This role was created in 2017 by Henrik Pingel.
