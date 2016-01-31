Signage OSX
=========

Ansible role for configuring signage osx machine environment.

Requirements
------------

* OSX
    * 10.10
    * 10.11
* Command Line Tools
* Homebrew

Role Variables
--------------

* `signageosx_hostname`: Defaults to not set.

Example Playbook
----------------

    - hosts: servers
      roles:
         - signage-osx

License
-------

BSD

Author Information
------------------

yuhki50 <yuhki50@gmail.com>
