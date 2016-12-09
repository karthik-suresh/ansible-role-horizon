Role Name
=========

Sets up a development version of Openstack-horizon works for kilo/liberty.


Role Variables
--------------

apt_package - Pre Requisite packages.
dest: Destination directory to install horizon.
branch: Git branch of openstack horizon which will be setup.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: karthik.horizonInstaller }

License
-------

MIT

Author Information
------------------

Karthik Suresh,
Distributed Systems enthusiast
