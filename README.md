# Barebones Vagrant Setup

------

## Setup Vagrant

#### 1. Install VirtualBox (https://www.virtualbox.org/)
#### 2. Install Vagrant (https://docs.vagrantup.com/v2/installation/)
#### 3. Configure Vagrantfile
Please check and configure your `/vagrant/Vagrantfile` to meet your virtual machnine requirements. 
#### 4. Start and Provision Vagrant machine 
* `cd vagrant`
* `vagrant up`
* `vagrant provision`

## Code Sync
Code under `/src/` are by default synced into your VM's `/appl/` folder. 