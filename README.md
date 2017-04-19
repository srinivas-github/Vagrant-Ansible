# Vagrant-Ansible
Automation tool (Vagrant and Ansible)

Description:
    Using Vagrant for launching VM and Using Ansible as Provision to configure the apache2 service.

1. clone the repo:
   git clone https://github.com/srinivas-github/Vagrant-Ansible.git
   cd Vagrant-Ansible
2. run the "vagrant up"

3. Trouble shooting:
   If you encounter the followng error then just add box as follows:
   

   "There are errors in the configuration of this machine. Please fix
   the following errors and try again:

   vm:
   * The box 'ubuntu/trusty64' could not be found."

   Add the box:
   vagrant box add ubuntu/trusty64 https://github.com/sepetrov/trusty64/releases/download/v0.0.5/trusty64.box

then again "vagrant up"
   
  

