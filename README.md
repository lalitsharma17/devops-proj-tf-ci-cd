#DevOps

### THis project Purpose:
By following this repository you can able to setup a DevOps CI/CD Pipeline using
- git
- Jenkins
- Maven
- Ansible
- Docker &
- Kubernetes




### Terraform Deploy for specific Project 

DevOps Project:
1.	Install Jenkins Server
a.	Prerequisites:
       Java v1.8x – Setup Runtime Environment
       Port 8080
-	GIT Installation – “yum install git -y” on the server
-	GIT plugins install on the Jenkins
-	Setup GIT path on Jenkins tools configuration

2.	Install Docker Host
a.	Prerequisites: 
-	Install and start service
-	Create a user to manage, ensure permission “usermod -aG docker <user-account>”
-	Download a docker image from hub.docker.com
-	Test by creating a container using tomcat from public registry if need be.
-	Validate

3.	Install Kubernetes Host
a.	Prerequisites:
-	Use ubuntu instance for this
-	Install python
-	Install Kubectl
-	Install Kops to setup your cluster, quick and easy
-	Deploy Ngnix container to test
-	Expose service to test

4.	Install Ansible Server
a.	Prerequisites:
-	Install python
-	Install python-pip
-	Install ansible
-	Create ansible admin account as ansibleadm
-	Grant sudo access using visudo command
-	Generate ssh-keygen
-	Copy keys on all ansible managed hosts using ssh-copy-id command
-	Install docker
-	Add ansibleadm account to docker group.
-	Do the ping test, validate.

