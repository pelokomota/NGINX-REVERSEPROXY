Vagrant.configure("2") do |config|
  config.vm.box = "generic/ubuntu1804"
  config.vm.provider "virtualbox" do |v|
    v.memory = 1024
  end

  config.vm.define "webapp" do |webapp|
    webapp.vm.network "private_network", ip: "172.17.177.50"
    end

end
