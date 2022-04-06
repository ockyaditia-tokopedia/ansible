1. `pip install ansible`
2. for upgrade ansible `pip install ansible --upgrade`
3. make sure if already installed `ansible all -m ping`
4. or using `ansible --version`
5. `ansible-playbook -i inventories/hosts playbook-001.yaml -v`
6. `ansible-playbook -i inventories/hosts playbook-001.yaml -v --ask-become-pass`
7. `ansible-galaxy init infinispan`
8. `ansible-vault encrypt_string 'admin' --name 'infinispan_admin_password'`
9. `ansible-vault create infinispan_admin_password.yaml`