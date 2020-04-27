# github.io-bingo

"github.io-bingo" is a simple bingo creation sheet made with php

#features

This bingo making sheet has 5 rows, and the range that appears on each is set in 15 steps. Also, the number will change each time you reload.

#Requirement

The necessary environment is the local server environment started by vagrant. Also, PHP version is 5.6

#installation

The official site is vagrant.com, so download it here.
Here's how to start a server with vagrant:

Move to home directory
cd

Assuming that multiple virtual machines will be created in the future, create a folder (MyVagrant) to combine them.
mkdir MyVagrant

Go to MyVagrant
cd MyVagrant

Create a folder to create a virtual machine (MyCentOS)
mkdir MyCentOS

Go to MyCentOS
cd MyCentOS

Create a Vagrantfile for virtual machine settings
vagrant init bento/centos-6.8

Edit the Vagrantfile and set the IP address of the virtual machine to 192.168.33.10.
sed -i '' -e 's/# config.vm.network "private_network", ip: "192.168.33.10"/config.vm.network "private_network", ip: "192.168.33.10"/' Vagrantfile

Start the virtual machine (takes a little time)
vagrant up

Check the status of the virtual machine
vagrant status

#Author
Atsuya kizaki
Chiba Institute of Technology Faculty of Information Science Department of Information Engineering
