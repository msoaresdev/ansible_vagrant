Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/xenial64"
  config.vm.network "public_network", ip: "192.168.25.204"
  config.vm.provision :ansible do |ansible|
    ansible.playbook = "playbook.yml"
    end
end    