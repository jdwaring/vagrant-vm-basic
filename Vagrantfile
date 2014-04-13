# -*- mode: ruby -*-
# vi: set ft=ruby :

# Vagrantfile API/syntax version. Don't touch unless you know what you're doing!
VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|

  config.vm.box = "hashicorp/precise32"
  config.vm.provision :shell, :path => "bootstrap.sh"

# Comment out this line if using IP address for hosting
 config.vm.network :forwarded_port, host: 1234, guest: 80

# Uncomment the line below to host website on IP address
#  config.vm.network "private_network", ip: "192.168.0.42"

end
