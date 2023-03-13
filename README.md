# devops-project
A devops project that demonstrate a simple pipeline using Jenkins, Ansible and Docker:
## Pre-requistes: 
- Having 3 EC2 server on AWS (Jenkins server, Ansible server, Webapp server)
 - push code to guithub
 - trigger the pipeline in Jenkins
 - Jenkins makes an ssh connection to Ansible
 - Ansible builds the docker image and push it to docker hub
 - Webapp server pull the image from docker hub and run it to execute the container
 - The app is live in the Webapp server
 
