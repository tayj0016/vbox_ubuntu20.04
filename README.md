# vbox_ubuntu20.04
Virtual Box build using Vangrant box bento/ubuntu-20

  `vagrant init bento/ubuntu-20.04`
  
If you are not on an admin account and are trying to modify your VM in an administrator cmd window, type these commands:

  `cd "C:\Program Files\Oracle\VirtualBox"`
  
  `VboxManage registervm "C:\Users\TaylorJW\VirtualBox VMs\<VM NAME>\<VM NAME>.vbox"`

Then verify by:

  `VBoxManage getextradata <VM NAME> enumerate`
  `vagrant up`
  `sudu apt update`
  `sudo apt upgrade`
  `curl -fsSL https://deb.nodesource.com/setup_lts.x | sudo -E bash - &&\
  `sudo apt-get install -y nodejs`
  `npm install -g @angular/cli`

  `ng new <PROJECT NAME>`

  `ng serve <PROJECT NAME> --host 0.0.0.0`
 
