Pipproxy
=========

This will create proxy for pip

Requirements
------------
None

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    ---
    - hosts: localhost
      remote_user: root
      become: true
      vars:
        mirror_pypi_url: originaljfrogdetails
      roles:
        - hemanth22.pipproxy

License
-------

MIT / BSD

Author Information
------------------

This role was created in 2021 by Hemanth BITRA.
