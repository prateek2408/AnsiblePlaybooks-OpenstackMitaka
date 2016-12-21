# AnsiblePlaybooks-OpenstackMitaka
Openstack Deployment using Ansible Playbook on Physical multi-node environment

Here are the scripts to deploy openstack on a multi-node environemnt Details are-
  1. Openstack Mitaka Relaease
  2. Controller, Network, Compute multi-node deployment mode supported.
  3. Installs heat and Magnum openstack components as well.
  
Steps-
    1. Just clone the directory to a machine where ansible is installed and make sure password-less authentication is there between ansible server and the hosts.
    2. Open the host file and change the host entires as per the environment
    3. ansible-playbook -i host site.yml
    4. Thats it you will have openstack mitaka up and running in some time :)
