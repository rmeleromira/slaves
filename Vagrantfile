# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.define "slave1" do |slave1|
    slave1.vm.box = "centos/7"
    slave1.vm.hostname = "slave1"
    slave1.vm.network "public_network",
      :dev => "br0",
      :mode => "bridge",
      :type => "bridge"


    slave1.vm.provider :libvirt do |lv|
      lv.memory = "2048"
      lv.cpus = "4"
    end
    slave1.vm.provision "ansible" do |ansible|
      ansible.vault_password_file = "vault-pass"
      ansible.playbook = "provision.yml"
    end
  end

  config.vm.define "slave2" do |slave2|
    slave2.vm.box = "centos/7"
    slave2.vm.hostname = "slave2"
    slave2.vm.network "public_network",
      :dev => "br0",
      :mode => "bridge",
      :type => "bridge"


    slave2.vm.provider :libvirt do |lv|
      lv.memory = "2048"
      lv.cpus = "4"
    end
    slave2.vm.provision "ansible" do |ansible|
      ansible.vault_password_file = "vault-pass"
      ansible.playbook = "provision.yml"
    end
  end

  config.vm.define "slave3" do |slave3|
    slave3.vm.box = "centos/7"
    slave3.vm.hostname = "slave3"
    slave3.vm.network "public_network",
      :dev => "br0",
      :mode => "bridge",
      :type => "bridge"


    slave3.vm.provider :libvirt do |lv|
      lv.memory = "2048"
      lv.cpus = "4"
    end
    slave3.vm.provision "ansible" do |ansible|
      ansible.vault_password_file = "vault-pass"
      ansible.playbook = "provision.yml"
    end
  end

  config.vm.define "slave4" do |slave4|
    slave4.vm.box = "centos/7"
    slave4.vm.hostname = "slave4"
    slave4.vm.network "public_network",
      :dev => "br0",
      :mode => "bridge",
      :type => "bridge"


    slave4.vm.provider :libvirt do |lv|
      lv.memory = "2048"
      lv.cpus = "4"
    end
    slave4.vm.provision "ansible" do |ansible|
      ansible.vault_password_file = "vault-pass"
      ansible.playbook = "provision.yml"
    end
  end

  config.vm.define "slave5" do |slave5|
    slave5.vm.box = "centos/7"
    slave5.vm.hostname = "slave5"
    slave5.vm.network "public_network",
      :dev => "br0",
      :mode => "bridge",
      :type => "bridge"


    slave5.vm.provider :libvirt do |lv|
      lv.memory = "2048"
      lv.cpus = "4"
    end
    slave5.vm.provision "ansible" do |ansible|
      ansible.vault_password_file = "vault-pass"
      ansible.playbook = "provision.yml"
    end
  end
end
