# minikube
Minikube installation on Amazon EC2 

Requirements:
1. Server with minimum 4GB RAM and 25G HD. Below environment was set up on Amazon EC2-CentOS

Installation steps:
- Install Kubectl. Follow official documentation at https://kubernetes.io/docs/tasks/tools/install-kubectl/
- Install Docker. Follow official documentation at https://docs.docker.com/engine/install/centos/
- Install Minikube: Follow official documentation at https://kubernetes.io/docs/tasks/tools/install-minikube/
- create service and deployment using attached definition files. Once, the pod will be running, the webapp can be accessed on     URL- http://IP:NodePort
