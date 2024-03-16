Learn Ansible (Second Edition) - Example Role
=========

A basic role to show how to create a role and publish it to Ansible Galaxy.

Requirements
------------

Apart from requiring root access via `become: yes` this role has no special requirements.


Role Variables
--------------

All of the variables can be found in the `vars` folder.

Dependencies
------------

None.

Example Playbook
----------------

An example playbook can be found below;

```yaml
- hosts: servers
  gather_facts: true
  become: yes
  become_method: sudo

  roles:
      - russmckendrick.ansible_role_learnansible_example
```

License
-------

BSD

Author Information
------------------

This role is published by [Russ McKendrick](http://russ.mckendrick.io/).