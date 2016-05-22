Vagrant.configure(2) do |config|
    config.vm.box = "ubuntu/trusty64"
    config.vm.hostname = "VerdonckJanosh"
    config.vm.network "forwarded_port", guest: 40, host: 4040
    config.vm.provision  "shell", path: "provision_nginx.sh"
    config.vm.provision  "shell", path: "provision_php.sh"
end
