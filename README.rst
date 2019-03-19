zoidy_ruby-vroom
================

An Ansible role to install rubies, and related.

Requirements
------------

Linux Mint or Ubuntu.

Example Playbook
----------------

It's simple to run the role from a playbook.

Add the role to the playbook::

  - hosts: servers
    roles:
       - role: zoidy_ruby-vroom

Then run the play::

  ansible-playbook path/to/site.yml -K

If you want to restrict what's installed to a specific group, use tags, e.g.,::

  ansible-playbook path/to/site.yml -K --tags ruby-vroom

License
-------

`GPLv3 <LICENSE>`__

