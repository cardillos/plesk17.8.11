# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|

# Download vagrantbox from https://app.vagrantup.com/cardillos/boxes/plesk17
config.vm.box = "cardillos/plesk17"
config.ssh.username = "zeald"
config.ssh.password = "admin"

config.vm.network "public_network", type:"dhcp", adapter:1
config.vm.network "private_network", ip:"192.168.35.77"

 config.vm.provider "virtualbox" do |vb|
    # Display the VirtualBox GUI when booting the machine
    vb.gui = true
    # Customize the amount of memory on the VM:
    vb.memory = "2048"
 end
end
