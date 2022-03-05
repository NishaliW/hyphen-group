
Pre-requsites
  Ansible


Steps to execute:
1. Download the repo to your local machine
2. Update hyphen-group/ansible-scripts/inventory/hosts file with the list of hosts you want to update
3. Update hyphen-group/ansible-scripts/kube_multinode_cluster.yml file with the inventory host name and home_dir variable
4. Execute the playbook --> ansible-playbook kube_multinode_cluster.yml
