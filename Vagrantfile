Vagrant.configure(2) do | config |
  config.vm.define "node1" do | node1 |
    node1.vm.box = "bento/ubuntu-20.04"
    node1.vm.network "private_network", ip: "192.168.33.11"
    node1.vm.hostname = "node1"
    node1.vm.provider "virtualbox" do | v |
      v.memory = 512
      v.cpus = 1
    end
  end

  config.vm.define "node2" do | node2 |
    node2.vm.box = "bento/ubuntu-20.04"
    node2.vm.network "private_network", ip: "192.168.33.12"
    node2.vm.hostname = "node2"
    node2.vm.provider "virtualbox" do | v |
      v.memory = 512
      v.cpus = 1
    end
  end
end