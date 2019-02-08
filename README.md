Role Name
=========

This role install and configure puppet agent into Debian, RedHat and CentOS7

Requirements
------------

Role Variables
--------------
Variables that are in defaults/main.yml, It has the variables:
  **environmentname** *Eg: testing, production, homolog. According your server configuration.*
  **puppetserver** *Eg: puppetserver.mafrait.com.br*
Dependencies
------------

Example Playbook
----------------

    - hosts: all
      roles:
         - { role: ansible-puppet-age'nt }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
