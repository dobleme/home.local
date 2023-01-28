# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "dobleme/fedora-workstation-37-amd64"
  config.vm.box_version = "1.7"
  config.vm.synced_folder ".", "/home/vagrant/home.local",
    owner: "vagrant", group: "vagrant",
    create: true
end
