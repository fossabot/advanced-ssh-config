Advanced SSH config
===================

Using ssh_config ProxyCommand, ssh calls advanced-ssh-config.py.

The new .ssh/config file become .ssh/config.advanced with new features and a better regex engine for the hostnames.
Each time the script is called, it recreate a whole new .ssh/config, so be careful, backup your old .ssh/config file !

Features
========

* better regex engine (gw.school-*.*.domain.net)
* aliases
* gateways (chain your ssh connections)
* includes (include sub files)
* real local command (execute a command on the local shell)
