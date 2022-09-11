# victor
student
DOCKER INSTALLATION
############################
#!/bin/bash
 Ubuntu Server 18.04 LTS (HVM),
 redhat ec2-instances creates ec2-users by default 
 ubuntu ec2-instances creats ubuntu user by default
-----
#!/bin/bash
sudo hostname docker
sudo apt update -y 
sudo apt install docker.io -y
sudo usermod -aG docker ubuntu 
sudo su - ubuntu
=========================
Docker commands need admins right or
 sudo priviledges to run docker commands 
