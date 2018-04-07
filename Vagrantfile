# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|

    # config.vm.define "centos7" do |centos|
    #     centos.vm.box = "centos/7"
    #     centos.vm.hostname = "centos7"
    #     centos.vm.network "private_network", ip: "192.168.56.111"
    # end

    config.vm.define "lamp" do |ubuntu|
        ubuntu.vm.box = "ubuntu/xenial64"
        ubuntu.vm.hostname = "lamp"
        ubuntu.vm.network "private_network", ip: "192.168.56.191"
    end

    # config.vm.provision "ansible_local" do |ansible|
    #    ansible.playbook = "setup.yml"
    #    ansible.compatibility_mode = "2.0"
    #    ansible.verbose = "vvvv"
    # end
end
