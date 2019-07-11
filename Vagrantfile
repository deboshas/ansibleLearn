# -*- mode: ruby -*-
# vi: set ft=ruby :

# All Vagrant configuration is done below. The "2" in Vagrant.configure
# configures the configuration version (we support older styles for
# backwards compatibility). Please don't change it unless you know what
# you're doing.
Vagrant.configure("2") do |config|
  config.vm.define "webserver" do |webserver|
  webserver.vm.box="ubuntu/trusty64"
  webserver.vm.network "private_network",ip:"192.168.0.2"
  webserver.vm.hostname="webserver"
end
config.vm.define "ansible" do |ansible|
  ansible.vm.box="ubuntu/trusty64"
  ansible.vm.network "private_network",ip:"192.168.0.254"
  ansible.vm.hostname="ansible"
end
end
