# ansible-openstack
Ansible deployment for Openstack

# Use this ansible command to run your playbook
```ansible-playbook ansible/main.yml -i hosts/inventory.hosts --ssh-common-args '-o StrictHostKeyChecking=no' --vault-password-file=.vault_pass```

# Use this playbook to make changes in your controller node
```ansible-playbook  ansible/controller.yml -i hosts/inventory.hosts --ssh-common-args '-o StrictHostKeyChecking=no' --vault-password-file=.vault_pass```

# Dont forget to create ansible vault and vault-password-file for storing secret.
<link>https://docs.ansible.com/ansible/latest/user_guide/vault.html</link>
