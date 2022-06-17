## Deploy a High-Availability Web App using CloudFormation
---
  
> ###### Infrastructure diagram
  
![infrastructure](/img/Erick_Udiagram.jpeg)  

### Scenario Handled  
Your company is creating an Instagram clone called Udagram.

Developers want to deploy a new application to the AWS infrastructure.

You have been tasked with provisioning the required infrastructure and deploying a dummy application, along with the necessary supporting software.

This needs to be automated so that the infrastructure can be discarded as soon as the testing team finishes their tests and gathers their results.  

### Files  

- /Scripts:
> - create.sh - script to create stack
> - dele_stack.sh - script to delete stack
> - update.sh - script to update stack

- ```/img``` - Screenshots of the workflow
- ```final-project-networking.yml``` - CloudFormation template for creating networking resources
- ```final-project_networking.json``` - parameters for final-project-networking.yml.
- ```our_servers.yml``` - CloudFormation template for creating servers
- ```our_servers.json``` - parameters for server components

### Usage

The Scripts folder contains bash scripts to perform various operations as described below  

> ###### To Create stack, Run  

> ```Scripts/create.sh stack-name final-project-networking.yml final-project_networking.json```

> ###### To Update stack, Run  

> ```Scripts/update.sh final-project-networking.yml final-project_networking.json```
> ###### To delete stack, Run

> ```Scritps/delete_stack.sh stack-name```
