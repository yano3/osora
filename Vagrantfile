# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|

  config.vm.define :centos7 do |config|
    config.vm.box = "centos/7"
    config.vm.synced_folder ".", "/vagrant"
    config.vm.network :forwarded_port, guest: 80, host: 10080
  end

end
