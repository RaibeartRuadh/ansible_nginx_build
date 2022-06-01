# -*- mode: ruby -*-
# vi: set ft=ruby :

ANSIBLE_NAME = "RaibeartAnsible"
SERVER_IP = "192.168.10.10"

Vagrant.configure("2") do |config|
  config.vm.box = "BOX1"
    config.vm.define "server" do |server|
    server.vm.hostname = "server"
    server.vm.network "private_network", ip: SERVER_IP
    server.vm.provision "ansible" do |ansible|
      ansible.playbook = "params/site.yml"	
    end
  end
end
