Role Name
=========

This role will install needed Jenkins students (slaves) for both linux and windows. That includes all the needed requirements by the project

Requirements
------------

All the python requierements are in the requirements.txt and can be installed with 

pip2 install -r requierements.txt

Ansible >=2.2

Ubuntu 16.04 targets (should work with 18.04 also, but not tested)

Create the node on Jenkins master

Add external role:

ansible-galaxy install kobanyan.jenkins-jnlp-slave

Role Variables
--------------

#

Dependencies
------------

https://galaxy.ansible.com/kobanyan/jenkins-jnlp-slave 

Example running
----------------

ansible-playbook -i hosts deploy_jenkins.yml -u 

License
-------

This project is released under the MIT License.


