DO Agent
=========

This role will install DigitalOcean Agent for Graphs monitoring.

Requirements
------------

* DigitalOcean droplet  
  This role should only be installed on a DigitalOcean droplet.

Example Playbook
----------------

    - name: Install DO Agent
      hosts: all
      become: true
      become_method: sudo
      roles:
        - mosufy.do-agent

License
-------

This codebase is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT)

Author Information
------------------

For any issues with installation or getting this to work, send an email to: [mosufy@gmail.com](mailto:mosufy@gmail.com)
