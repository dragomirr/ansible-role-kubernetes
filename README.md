Kubernetes
==========

Install kubernetes cluster on ubuntu 20.04+

Requirements
------------

Collections:

  * ansible.posix
  * community.general

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: control_plane
      roles:
         - { role: dragomirr.kubernetes, kubernetes_control_plane: true }

    - hosts: workers
      roles:
         - { role: dragomirr.kubernetes }

License
-------

BSD
