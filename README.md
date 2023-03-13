# devops-project
A devops project that demonstrate a simple pipeline using Jenkins, Ansible and Docker:
## Pre-requistes: 
- Having 3 EC2 server on AWS (Jenkins server, Ansible server, Webapp server)
 - push code to guithub
 - trigger the pipeline in Jenkins
 - Jenkins makes an ssh connection to Ansible
 - Ansible builds the docker image and push it to docker hub
 - In the playbook file, Ansible server will pull the image from docker hub and run it in the Webapp server
 - The app is live in the Webapp server
 
