# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  config.vm.box = "stackroute/xenial"
  config.vm.box_url = "http://192.168.1.7/vagrant/boxes/xenial64.box"
  config.vm.network "forwarded_port", guest: 8080, host: 8087
  config.vm.provision :puppet
end
