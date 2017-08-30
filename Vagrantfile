# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/trusty64"
  config.vm.provision "shell", path: "config/config.sh"

  config.vm.provider "virtualbox" do |v|
    v.name = "Docker Virtual Machine"
  end
end
