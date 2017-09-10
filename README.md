Squid
=========

This role installs and configures Squid as a proxy server.

Requirements
------------

None.

Role Variables
--------------

| Variable | Description | Default |
|----------|-------------|---------|
| squid_cache_dir | Main squid config file | /var/spool/squid |
| squid_conf_dir | Location of squid config files | /etc/squid |
| squid_conf_file | Main squid config file | squid.conf |
| squid_log_dir | Location of squid log files | /var/log/squid |
| squid_package_name | Name of squid package in package manager | squid |
| squid_service_name | Name of squid service | squid |
| squid_user | User running squid | proxy |
| squid_group | Group running squid | proxy |

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: proxyServers
      roles:
         - { role: TheRealJohnDavies.squid }

License
-------

BSD

Author Information
------------------

John Davies (http://github.com/TheRealJohnDavies)

