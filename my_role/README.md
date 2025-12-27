Role Name
=========
common_system_tasks

Role Description 
================
This role automates basic system setup tasks including installing and enabling a specified service, creating a configurable number of users, executing a script to list all existing users on the system, and triggering handlers to notify or restart services upon successful installation.


Requirements
==============

- Ansible 2.9 or higher
- Target system must be a Linux-based OS (Debian/Ubuntu recommended)
- Root or sudo privileges are required to install services, manage users, and modify system files
- The script used to list users must exist on the control node and be executable

Role Variables
===============

1- Description: Name of the service to install and enable

    Type: string
    
2- Description: List of users to be created on the system

    Type: list
    
3-Description: List of users to be created on the system

    Type: list
    
Dependencies
================

None

Example Playbook
================

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
========

BSD

Author Information
==================

Lina Mohamed
DevOps Engineer

