# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|

  config.vm.define :centos7 do |config|
    config.vm.box = "centos/7"
    config.vm.synced_folder ".", "/vagrant"
    config.vm.network :forwarded_port, guest: 80, host: 10080
  end

  config.vm.define :centos6 do |config|
    config.vm.box = "centos/6"
    config.vm.synced_folder ".", "/vagrant"
    config.vm.network :forwarded_port, guest: 80, host: 10081
  end

  config.vm.define :bionic do |config|
    config.vm.box = "ubuntu/bionic64"
    config.vm.synced_folder ".", "/vagrant"
    config.vm.network :forwarded_port, guest: 80, host: 10082
  end

  config.vm.define :xenial do |config|
    config.vm.box = "ubuntu/xenial64"
    config.vm.synced_folder ".", "/vagrant"
    config.vm.network :forwarded_port, guest: 80, host: 10083
  end

end
