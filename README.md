Role Name
=========

Role installs ansible.

Requirements
------------


Role Variables
--------------

Dependencies
------------

* dbs_proxyconf


Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: dbs_ansible, tags ["ansible"]  }

License
-------

BSD

Author Information
------------------
it's me
