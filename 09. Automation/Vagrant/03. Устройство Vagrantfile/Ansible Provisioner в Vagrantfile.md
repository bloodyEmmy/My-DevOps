#flashcards/automation/Vagrant 
***
Прописывается [[Ansible Provisioner в Vagrant|Ansible провижионер]] в [[Vagrantfile]].
***Синтаксис.***
```Ruby
config.vm.provision "ansible" do |ansible|
  ansible.playbook = "playbook.yml"
end
```