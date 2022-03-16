This is an optional task from ALX on how to install vagrant on your pc

Since i use ubuntu, I only have the tutorial step, on how to install it here :

Here's how to install vagrant on your personal pc 

Ubuntu
Open the Terminal application:
Now you will execute command line in your Terminal (each of them start with $)
Install VirtualBox: $ sudo apt-get install virtualbox
Install Vagrant: $ sudo apt-get install vagrant
Add the Ubuntu 20.04 (Focal) image to your box list: $ vagrant box add ubuntu/focal64 Warning: this step can take time
Many other images are available here : https://alx-intranet.hbtn.io/rltoken/i2j9GY2ou1zBvZ9wUeavRw

Create your first virtual machine:
$ vagrant init ubuntu/focal64 -> it will generate a Vagrantfile with base = "ubuntu/focal64" - you don’t have to execute this command line everyday, only once, to create a new virtual machine

$ vagrant up -> it will start your virtual machine

$ vagrant ssh -> now you are inside your virtual machine.


This is an optional task from ALX on vagrant installation.
