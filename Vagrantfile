# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vagrant.plugins = ["vagrant-reload", "vagrant-scp"]
end

saltmaster_box_vagrantfile = './vagrant/Vagrantfile.saltmaster-box'
load saltmaster_box_vagrantfile if File.exists?(saltmaster_box_vagrantfile)
