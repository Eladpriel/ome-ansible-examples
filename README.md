# ome-ansible-examples

This examples was prepared for Dell MX customers that would like to use Ansible to configure their Chassies, 
this is not offcial example but all of them were tested and found working.


Prerequisites
Ansible >= 2.10.0
Python >=2.7.17 or >=3.6.5
Dell EMC OpenManage Enterprise-Modular versions 1.20.00 and above.
To run the iDRAC modules, install OpenManage Python Software Development Kit (OMSDK) using pip install omsdk --upgrade or from Dell EMC OpenManage Python SDK

Installation
From galaxy:
ansible-galaxy collection install dellemc.openmanage

For offline installation on the Ansible control machine, download the required tar archive version of the collection from Dell EMC OpenManage collection and run the command given below:
ansible-galaxy collection install dellemc-openmanage-<version>.tar.gz

From github:
Install the collection from the github repository using the latest commit on the branch 'collections'
ansible-galaxy collection install git+https://github.com/dell/dellemc-openmanage-ansible-modules.git,collections

Notes:
I used virtual env in order to have issues with OS dependencies 
