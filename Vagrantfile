Vagrant.configure("2") do |config|

    config.vm.box = "ubuntu/jammy64"
    config.vm.provision "shell", inline: "/vagrant/bin/xyn provision"
    config.vm.hostname = "xyn"
    config.vm.define "xyn"
    config.vm.provider "virtualbox" do |v|
        v.memory = 3072
        v.cpus = 3
    end

end
