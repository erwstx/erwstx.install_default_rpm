Role Name
=========

A simple Role which ensure that a list of packages are installed

Requirements
------------

N/A

Role Variables
--------------

install_default_rpm_packages_list: List of package we want to manage

Dependencies
------------

N/A

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
