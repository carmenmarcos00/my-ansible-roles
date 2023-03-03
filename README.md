Consul role
=========

Ansible role to deploy Consul in a multi-cluster environment.

Requirements
------------
By now it is only being developed for Ubuntu, Debian and Kali Linux. Further releases will include more target systems.
It is needed to have Ansible installed.

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Example of how to use the role:

- name: Install and configure Consul using Ansible role
  hosts: localhost
  gather_facts: yes
  become: yes

  tasks:
    - name: Install and configure Consul using Ansible role
      import_role:
        name: consul

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
