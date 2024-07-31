xcc_mount
=========
 
This is a role created for mounting an ISO image in a Lenovo server managed by XCC.
 
Requirements
------------
 
* Ansible
* xcc managed server.
* community.general
 
Role Variables
--------------
  
### defaults/main.yml
 
* username: Username credential to login into xcc.
* password: Password credential to login into xcc.
* baseuri: Redfish API URL.
 
### vars/main.yml

 
Dependencies
------------
 
---
 
Example Playbook
----------------
 
   - hosts: localhost
     become: true
     roles:
       - role: xcc_mount
         username: "My_user"
         password: "My_passwd"
         base_uri: "[ip:port]"
       
 
License
-------
 
-
 
Author Information
------------------
 
Oviedo Matias
Schinca Mauro
