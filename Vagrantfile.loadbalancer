# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/trusty64"
  config.vm.hostname = "loadbalancer"
  config.vm.network :public_network, ip: "192.168.1.100"

  config.ssh.password = "vagrant"

  config.vm.provider "virtualbox" do |vb|
    vb.cpus = 1
    vb.memory = 512
  end
end
