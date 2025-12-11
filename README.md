
Role Name:
wtf_nginx_role
=========

This role installs and enables nginx service on a linux machine that uses apt package manager

#A brief description of the role goes here.

Requirements:
You need to have an ansible master node/controller and 1 or more conttrolled node
You need to have an inventory file with the host(s) details
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables:
Null
--------------

#A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies:
Null
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

#Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License:
MIT
-------

BSD

Author Information
------------------
Women Techsters Fellowship Class of 2025 DevOps Track

#An optional section for the role authors to include contact information, or a website (HTML is not allowed).
# ansible-role-wtf_nginx_role
This repository holds an ansible  role that will install  and start nginx service on debian based linux systems
