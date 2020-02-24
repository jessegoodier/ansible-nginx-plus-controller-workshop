# ansible-nginx-plus-controller-workshop

The goal of this workshop is to install NGINX Plus and add it to NGINX Controller using Ansible.

sudo apt-add-repository --yes --update ppa:ansible/ansible
sudo apt update
sudo apt upgrade
ansible-playbook 3_nginx_plus.yaml  -i hosts -b

