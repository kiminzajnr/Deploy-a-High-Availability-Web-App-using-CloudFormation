# Deploy a High-Availability Web App using CloudFormation
  
## Infrastructure diagram

![infrastructure](/img/Erick_Udiagram.jpeg)  

## Scenario  
Your company is creating an Instagram clone called Udagram.

Developers want to deploy a new application to the AWS infrastructure.

You have been tasked with provisioning the required infrastructure and deploying a dummy application, along with the necessary supporting software.

This needs to be automated so that the infrastructure can be discarded as soon as the testing team finishes their tests and gathers their results.  

## Files  

- `/Scripts/create.sh` - Creates stack
- `/Scripts/delete_stack.sh` - Deletes stack
- `/Scripts/update.sh` - Updates stack
- `/img` - Screenshots of the workflow
- `final-project-networking.yml` - CloudFormation template for creating networking resources
- `final-project_networking.json` - parameters for final-project-networking.yml.
- `our_servers.yml` - CloudFormation template for creating servers
- `our_servers.json` - parameters for server components

## Usage

The Scripts folder contains bash scripts to perform various operations as described below  

## Create stack  

```
Scripts/create.sh stack-name final-project-networking.yml final-project_networking.json
```

## Update stack 

```
Scripts/update.sh final-project-networking.yml final-project_networking.json
```
## delete stack

```
Scritps/delete_stack.sh stack-name
```

## [Live App Url](http://proje-webap-75ukg6xr0oxq-155649170.us-east-1.elb.amazonaws.com/)

⚠️ **Currently not available** ⚠️
