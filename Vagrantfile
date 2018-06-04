Vagrant.configure("2") do |config|
  config.vm.box = "bento/centos-7.4"
  config.vm.hostname = "sensu-up-and-running-01"
  config.vm.network "private_network", type: "dhcp"
  config.vm.provision "shell", path: "sensu-provisioning-script.sh"
  config.vm.provider "virtualbox" do |vb|
    vb.memory = 1024
  end
end
