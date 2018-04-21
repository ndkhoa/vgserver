# -*- mode: ruby -*-
# vi: set ft=ruby :

VAGRANTFILE_API_VESION = "2"
HOST_NAME = "loadbalancer"
HOST_IP = "192.168.1.200"

Vagrant.configure(VAGRANTFILE_API_VESION) do |config|
  config.vm.box = "ubuntu/xenial64"
  config.vm.hostname = HOST_NAME
  config.vm.network "public_network", ip: HOST_IP

  config.vm.provider "virtualbox" do |vb|
    vb.gui = false
    vb.memory = 1024
    vb.cpus = 1
  end
end
