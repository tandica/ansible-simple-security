# ansible-simple-security

## Overview

A growing collection of ansible playbooks that perform security and administrative tasks. 

1. ssh users 

This playbook creates a new admin user and assigns it an SSH key. It also disbales root login for SSH.

The variables `admin_user`, `groups` and `ssh_key_path` can be configured in the command line when running the playbook. This allows for admin type users to be configured more easily, with accordance to individual user name, groups and having their own SSH key. 

It confirms that root login is disabled. 

2. unauthorized logins

This playbook gets and lists unauthorized logins for local and ssh. 


3. User and group management 

This playbook adds users to a group. 

