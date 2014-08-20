# -*- mode: ruby -*-
# vi: set ft=ruby :

VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|

  config.vm.define :vagrant do |node|
    node.vm.box = "chef/centos-6.5"
    node.vm.network :private_network, ip: "192.168.33.11"
  end

end
