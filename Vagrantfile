# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|

  config.vm.define :centos8 do |config|
    config.vm.box = "centos/8"
    config.vm.synced_folder ".", "/vagrant"
    config.vm.network :forwarded_port, guest: 80, host: 20080
  end

  config.vm.define :centos7 do |config|
    config.vm.box = "centos/7"
    config.vm.synced_folder ".", "/vagrant"
    config.vm.network :forwarded_port, guest: 80, host: 20081
  end

  config.vm.define :jammy do |config|
    config.vm.box = "ubuntu/jammy64"
    config.vm.synced_folder ".", "/vagrant"
    config.vm.network :forwarded_port, guest: 80, host: 10080
  end

  config.vm.define :focal do |config|
    config.vm.box = "ubuntu/focal64"
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

  config.vm.define :debian11 do |config|
    config.vm.box = "debian/bullseye64"
    config.vm.synced_folder ".", "/vagrant"
    config.vm.network :forwarded_port, guest: 80, host: 30080
  end

  config.vm.define :debian10 do |config|
    config.vm.box = "debian/buster64"
    config.vm.synced_folder ".", "/vagrant"
    config.vm.network :forwarded_port, guest: 80, host: 30081
  end

end
