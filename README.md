Role Name
=========

A brief description of the role goes here.

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

pihole installation variables:

* git_clone_location: local directory for pihole checkout
* pihole_interface: what network interface pihole will use
* pihole_ipv4: ipv4 address for the pihole server
* pihole_ipv6: ipv6 address for the pihole server
* pihole_dns_1 ... 4: up to 4 upstream DNS servers for the pihole to forward to
* pihole_query_logging: enable or disable pihole logging of DNS queries
* pihole_install_web_server: enable or disable pihole installing lighttpd & php
* pihole_install_web_interface: enable or disable installation of web admin interface
* pihole_blocking_enabled: enable or disable pihole blocking
* pihole_password: password for the pihole web interface


Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
