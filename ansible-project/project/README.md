Role Name
=========

This role is used to spin up EC2 instances on AWS

Requirements
------------

1. Python boto3 package
2. AWSCLI
3. amazon.aws ansible collection

Role Variables
--------------

All variables are defined in the project/defaults/main.yml file. Varaibles include:
---
instance_type
region:
image_id_ubuntu: 
image_id_amz_linux: 
key_name: 
security_group: 


Dependencies
------------
Dependencies include:
1. amazon.aws

Example Playbook
----------------

You can find example playbook in the main.yml file in the root directory of this project. 

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
