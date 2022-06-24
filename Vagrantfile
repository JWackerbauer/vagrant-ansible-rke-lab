Vagrant.configure("2") do |config|
  config.vm.box = "bento/ubuntu-20.04"
    
  # Use :ansible or :ansible_local to
  # select the provisioner of your choice
  config.vm.provision :ansible do |ansible|
    ansible.playbook = "ansible/playbook.yml"
  end
end
