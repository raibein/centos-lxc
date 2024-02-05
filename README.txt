# pre-requisite
===============
1. client machine install sshpass. 
    Ubuntu: sudo apt install sshpass 
    CentOs: yum install sshpass


# Installing Docker
===================
1. To install the pre-requisite packages using ‘YUM’ module
- name: “Installing Docker Prerequisite packages”

2. To download ‘docker-ce.repo’ file to ‘/etc/yum.repos.d’ directory using ‘get_url’ module
- name: “Configuring docker-ce repo”

3. To install docker using ‘YUM’ module
- name: “ Installing Docker latest version”

4. To start and enable the docker service using ‘service’ module
- name: “ Starting and Enabling Docker service”


# Test commands
===============
1. ping the list of servers and host : ansible all -i ./inventory/hosts -m ping
2. run ansible playbook : ansible-playbook playbook.yml -i ./inventory/hosts -v


# Installing vagrant
====================
https://phoenixnap.com/kb/how-to-install-vagrant-on-centos-7


# Configuration DNS in CentOs
=============================
1. https://www.redhat.com/sysadmin/dns-configuration-ansible

2. https://docs.ansible.com/ansible/latest/collections/community/dns/hosttech_dns_record_sets_module.html


# Configuration IP Address in Second server
===========================================
1. https://www.cyberciti.biz/faq/howto-setting-rhel7-centos-7-static-ip-configuration/


# SSH copy from main Server to hosts
====================================
1. Go to the server machine (192.168.140.238) .ssh directory : cd .ssh
2. Generate the SSH Key : 
3. Copy SSH from main server (192.168.140.238) to the host machine (192.168.122.227): ssh-copy-id -i id_rsa.pub root@192.168.122.227


