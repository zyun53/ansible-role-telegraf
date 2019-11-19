Vagrant.configure("2") do |config|
  config.vm.box = "generic/freebsd12"
  config.vm.provision "ansible" do |ansible|
    ansible.playbook = "tests/test.yml"
  end
end
