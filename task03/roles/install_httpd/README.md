Role Name
=========

The role installs the Apache Server, opens 80/TCP port and creates a samle page.


Role Variables
--------------

- destination_path: a path for creating an index.html file 
- text_in_file: a text in the index.html file
- tcp_port: a port to open in the firewall


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }


Author Information
------------------

Denis Ziulikov
