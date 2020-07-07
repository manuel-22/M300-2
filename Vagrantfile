    # Modul300 - TBZ
    # Manuel Behringer
    # Date: 07.07.2020
    
    Vagrant.configure("2") do |config|
    
      config.vm.box = "ubuntu/xenial64"
    
      config.vm.box_check_update = false
    
      # config.vm.network "public_network", ip: "172.17.120.64"
      config.vm.network "public_network"
    
      config.vm.provider "virtualbox" do |vb|
    
         vb.gui = false
    
         vb.memory = "2048"
      end
    
     config.vm.provision "shell", path: "config.sh"
    
    end