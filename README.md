# learning-app-ecommerce_ansible
this https://github.com/kodekloudhub/example-voting-app automated with ansible roles and terraform 

first update inventory.yml with your nodes

vault password is in file : vault.pw

first run playbook for isntalling jenkins on node and all required software: ansible-playbook -i inventory.yml playbook.yml --tags add_jenkins --ask-vault-pass -kK
