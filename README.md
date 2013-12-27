nginx-passenger
===============

Ansible roles for Ubuntu 12.04

Put in ansible project in folder: 
    
    roles/nginx-passenger 


Example of using in site.yml

    ---

    - name: apply common configuration to all nodes
      hosts: all
      user: root

      roles:
        - nginx-passenger