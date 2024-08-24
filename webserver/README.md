Role Name
=========

This is a role created for demonstration purposes that configures a basic nginx webserver with a minimal configuration.
 
Requirements
------------
 
* Ansible
* Jinja2ed.

Role Variables
--------------

### defaults/main.yml
Default nginx installation variables.
 
* nginx_version: Specific version of nginx to install
* nginx_custom_directory: Custom directory for nginx installation
 
### vars/main.yml
Here we define variables that have high precedence and aren't intended to be changed by the play.
 
* nginx_custom_directory: Custom directory for nginx installation

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
- hosts: all
    become: true
    roles:
      - webserver
```

License
-------

Apache-2.0

Author Information
------------------

Ivo Karaneshev
