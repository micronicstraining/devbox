# devbox
A Vagrant VM based on Ubuntu 14 i386 for Python development.  

Setup
------

0. Install VirtualBox

1. Install Vagrant

https://www.vagrantup.com/downloads.html

2. Install git 

3. Clone this repository:

$ git clone https://github.com/micronicstraining/devbox

2. Go to devbox directory

$ cd devbox

3. Initialize environment.

$ vagrant up

4. Log in and do development work.  

Username/password -> vagrant/vagrant

5. Halt environment when finished.

$ vagrant halt

Note: If you prefer to develop on your local machine then look at the Vagrantfile and provision your system accordingly.  

This box has the following dependencies:
- python 2 & 3 pip, virtualenv
- scapy for python 2
- wireshark
- sublime text 3
- pycharm

