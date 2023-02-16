# learning-app-ecommerce_ansible
this https://github.com/kodekloudhub/learning-app-ecommerce automated with ansible roles

it can be installed on any distribution

first update inventory.yml with your nodes

vault password is in file : vault.pw

then run play like this:  ansible-playbook -i inventory.yml playbook-lamp.yml  --ask-vault-pass -kK
