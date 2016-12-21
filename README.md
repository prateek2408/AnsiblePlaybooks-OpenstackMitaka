# AnsiblePlaybooks-OpenstackMitaka
Openstack Deployment using Ansible Playbook on Physical multi-node environment

Here are the scripts to deploy openstack on a multi-node environemnt Details are-

    Openstack Mitaka Relaease
    Controller, Network, Compute multi-node deployment mode supported.
    Installs heat and Magnum openstack components as well.

Steps-

    Just clone the directory to a machine where ansible is installed and make sure password-less authentication is there between ansible server and the hosts.
    Open the host file and change the host entires as per the environment
    ansible-playbook -i host site.yml
    Thats it you will have openstack mitaka up and running in some time :)
