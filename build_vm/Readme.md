#How to build your own Virtual Machine?
###The following steps shows how you can spin up a Virtual Machine for tool Archie :

1. Install [vagrant] (https://www.vagrantup.com/downloads.html) and [virtualbox] (https://www.virtualbox.org/wiki/Downloads) on your host machine.
2. Download the [Vagrantfile] (https://github.com/SoftwareEngineeringToolDemos/FSE-2014-Archie-Smart-IDE/blob/master/build_vm/Vagrantfile) from [build-vm] (https://github.com/SoftwareEngineeringToolDemos/FSE-2014-Archie-Smart-IDE/blob/master/build_vm) folder on your machine and save it in a folder where you want to install the VM.
3. From the host, navigate to that folder and execute the command : "vagrant up"

###Note :
 -  The Virtual Machine will boot up quickly and but the "vagrant up" command runs for nearly half an hour to complete as it provisions the VM for use when ran for the first time.
 -  Deploys Base Vagrant Box : [Ubuntu 14.04 Desktop] (https://vagrantcloud.com/box-cutter/boxes/ubuntu1404-desktop)
 -  Default VM Login Credentials:  
      user: vagrant  
      password: vagrant

###References :
 -  Vagrant tutotial by Dustin Barnes,[Vagrant Tutorial](http://www.dev9.com/article/2014/9/dev-environments-with-vagrant)    
