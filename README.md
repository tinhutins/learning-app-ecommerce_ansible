# learning-app-ecommerce_ansible
this https://github.com/kodekloudhub/learning-app-ecommerce automated with ansible roles
it can be installed both on debian and centos systems
first update inventory.yml with your nodes 
then run play like this:  ansible-playbook -i inventory.yml playbook-lamp.yml  --ask-vault-pass -kK
