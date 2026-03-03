vector-role
=========

This role install Vector

Requirements
------------

* Ansible 2.19 or higher
* Debian-based system (tested on Debian 12)

Role Variables
--------------

### Defaults Variables
| Name           | Default Value | Description                      |
| -------------- | ------------- | -------------------------------- |
| vector_version | 0.44.0        | The version of Vector to install |

### Vars Variables
| Name               | Default Value           | Description                               |
| ------------------ | ----------------------- | ----------------------------------------- |
| vector_config_path | /etc/vector/vector.yaml | The path to the Vector configuration file |

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
