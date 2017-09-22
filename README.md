--Ansible copy install Galera Cluster with MySQL 

1. Git clone this source to root directory
2. Run command  #ansible-playbook -i hosts galera.yml --private-key='/path-to-ssh-key' -v

Follow this guide https://www.digitalocean.com/community/tutorials/how-to-configure-a-galera-cluster-with-mysql-5-6-on-ubuntu-16-04