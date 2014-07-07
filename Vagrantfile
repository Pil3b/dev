VAGRANTFILE_API_VERSION = "2"

Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/trusty64"

  config.vm.provision 'ansible' do |ansible|
     ansible.playbook = "playbook.yml"
  end
end


