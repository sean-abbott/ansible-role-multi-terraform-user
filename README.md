multi-terraform-user
=========

A role to install multiple terraform versions and an alias to switch between them.

Requirements
------------

N/A

Role Variables
--------------

terraform_version_list: a list of dictionaries with versions, urls, and hashes to download terraform

Dependencies
------------

N/A

Example Playbook
----------------


    - hosts: mydesktop
      roles:
         - { role: multi-user-terraform }

License
-------

Totes open? Public Domain? Maybe quote me if you use this, but really, no one will because it's very tailored to me.

Author Information
------------------

Sean's getting old and is starting to do this shit instead of play video games.
