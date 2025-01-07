# rke2-k8s-cluster
# Referrence: https://github.com/JamesTurland/JimsGarage/tree/main/Ansible/Playbooks/RKE2
# Requirements: Ansible version > 2.10
# etc/hosts
server1 10.24.28.51
server2 10.24.28.52
server3 10.24.28.53
agent1 10.24.28.54
agent2 10.24.28.55 
agent3 10.24.28.56
#  sudo ansible-playbook site.yaml -i inventory/hosts.ini --key-file ~/.ssh/id_rsa
