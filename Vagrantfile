# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.network "public_network"
    (1..5).each do |count|
    config.vm.define "docker#{count}" do |docker|
      docker.vm.box = "centos/7"
      docker.vm.provision "shell", path: "install_docker.sh"
      docker.vm.provision "shell", inline: "yum -y install git"
      docker.vm.provision "shell", inline: "git clone https://github.com/jpetazzo/orchestration-workshop"
    end
  end
end
