Role Name
=========

A simple Role which ensure that a list of packages are installed

Requirements
------------

None

Role Variables
--------------

install_default_rpm_packages_list: List of package we want to manage

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
	 - erwstx.install_default_rpm

-------

BSD

Author Information
------------------

erwstx@GitHub
