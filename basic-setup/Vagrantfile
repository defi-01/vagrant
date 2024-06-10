Vagrant.configure(2) do |config|
    # image Ubuntu 20.04 LTS
    config.vm.box = "ubuntu/trusty64"
    # don't check this repository for updates
    config.vm.box_check_update = false
  
    config.vm.provider "virtualbox" do |vb|
      # name VM
      vb.name = "vm1"
      # volume RAM
      vb.memory = 2048
      # count of processor cores
      vb.cpus = 2
    end
    
    # hostname VM
    config.vm.hostname = "vm1"
    config.vm.network "public_network", type: "dhcp", bridge: "Intel(R) Wireless-AC 9462"
end