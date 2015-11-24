# -*- mode: ruby -*-
# vi: set ft=ruby :

VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|

  config.vm.box = "centos/7"

  config.vm.define "docker1" do |docker1|
    docker1.vm.hostname = "docker1.local"
    docker1.vm.network "private_network", ip: "192.168.56.2"
    docker1.vm.provision "shell", path: "docker-init"
    docker1.vm.provider "virtualbox" do |v|
      v.memory = 2048
    end
  end
end
