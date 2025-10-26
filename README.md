# myPythonDockerRepo
Deploy Python App into Kubernetes Cluster using kubectl Jenkins Pipeline | Containerize Python App and Deploy into EKS Cluster | Kubectl Deployment using Jenkins

myPythonDockerRepo
This a python based app and containerized. you can clone - https://github.com/AKbunnyThakur/myPythonDockerRepo . This repo also have Jenkinsfile for automating the following:

Automating Docker image creation
Automating Docker image upload
Automating Docker container provisioning
You can configure pipeline in your Jenkins instance(Docker also installed) by creating a Declarative pipeline.

Make sure you do the following:

Create Credentials for connecting to Docker registry
Create scripted pipeline using Jenkinsfile from this repo
Change registry per your user name = "your_username/mypython-app-may20"
Update your credentials ID in Pipeline you are creating.
Open port 8096 in Ec2 instance.
