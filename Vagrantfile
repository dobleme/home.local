# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "fedora-workstation-37-1.7-amd64"  
  config.vm.synced_folder ".", "/home/vagrant/home.local",
    owner: "vagrant", group: "vagrant",
    create: true
end
