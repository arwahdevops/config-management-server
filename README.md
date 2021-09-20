# Server Configurations & Deployer
Configuration management &amp; code deployer using Ansible
# How To Provisioning
ansible-playbook -i inventory playbooks/setup/nginx.yml --ask-become-pass -b
# How To Deploy
ansible-playbook -i inventory playbooks/deploy/deploy-app.yml --ask-become-pass -b