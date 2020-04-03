# pi_networking
A repository for ansible playbooks to set up raspberry pi's as networking gear.

TL;DR - Fill out the sample.inventory, run `ansible-playbook -i sample.inventory playbooks/main.yaml`

## Requirements:
1. Ansible 2.8.5+
2. AWS Account with Route 53 Domain
3. At least 1 raspberry pi (only tested on 3B+ & 4)
4. RPI CentOS Image: Download - http://mirror.chpc.utah.edu/pub/centos-altarch/7.7.1908/isos/armhfp/

## Steps
1. Run the CloudFormation Templates in your AWS Account
2. Extract the exports in the sample.inventory
3. Fill in the rest of the info for your inventory
4. Run the command above
5. Debug
