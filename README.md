Basic python dev framework with virtualenv and virtualenvwrapper

# Prerequisite

- [VirtualBox](http://www.virtualbox.org/)
- [VirtualBox Extension Pack](https://www.virtualbox.org/wiki/Downloads)
- [Vagrant](http://www.vagrantup.com/)

# Usage

Assuming you have met the above requirements to provision a new Vagrant VM:

        $ cd folder Vagrantfile
        $ vagrant up
        $ vagrant ssh

# Specification

The above will build a VM running Ubuntu with the following installed and configured:

    1. Ansible (for provisioning)
    2. Git
    3. Python
    4. virtualenv
    5. virtualenvwrapper
    
--------------------------------------------------------------------- 
Created by [Michal Wiacek](https://github.com/michalwiacek)
