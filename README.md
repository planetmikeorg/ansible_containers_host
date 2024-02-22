Container Host 
=========

* Work-in-Progress


Configure an EL host to run Planet's containers. 

Requirements
------------

An EL host that has been baselined. 

Role Variables
--------------

Check defaults/main.yml, vars/main.yml, for now.

Dependencies
------------
planetmikeorg.baseline_el


Example Playbook
----------------


    - name: Linux
      hosts: all
      become: true
      vars:
        update_os: true
      roles:
        - planetmikeorg.containers_host

License
-------

BSD

Author Information
------------------

Michael Cleary - PlanetMike.Org
