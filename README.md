# k8s_cluster_ansible
Ansible Playbook to provision multi node kubernetes cluster on ec2
## Features
- Full automation using the playbook
- Provisioning on AWS 
- Mutli-Node cluster
- Add more and more nodes by just running the plays
- Automatic join worker nodes to master
## Installation
### Prerequisites
- Create a ansible vault for aws access key ID and secret key
- Must have dynamic inventory configured
### To run master playbook (Master Node)
ansible-playbook --vault-id .....@prompt Master.yml
### To run worker playbook(Linux Worker Node)
ansible-playbook --vault-id .....@prompt Linux-worker.yml
