# Udacity Nano Degree - Cloud DevOps Nano Degree Program

## Project #2 - Deploy a Highly Available Web App using CloudFormation

### Infrastructure Architectural Diagram:
<img src="./Udacity - Deploy a High-Availability Web App using CloudFormation - v1_0 (5)-Page-2.jpg">


### Description:
In this project, you will deploy web servers for a highly available web app using CloudFormation. You will write the code that creates and deploys the infrastructure and application for an Instagram-like app from the ground up. You will begin with deploying the networking components, followed by servers, security roles and software.

### Files included are:
```sh
* /Images-of-result-deploy : Screenshot the result of deploy.
* /App of Udagram : Udagram App Code (Bootssrap CSS framework, Font, and JavaScript libraries needed for the website to function etc ...)
* create.sh : Cloudformation create stack script. 
* update.sh : Cloudformation update stack script.
* destroy.sh : Cloudformation delete stack script.
* infrastructure_networkandserver.yml : Udagram Project's CloudFormation script.
* infrastructure_networkandserver.json : Udagram Project's CloudFormation script parameters.
```

### Instruction to deploy:
Just run;
```sh
> ./create.sh UdagramApp infrastructure_networkandserver.yml infrastructure_networkandserver.json
```

#### Credits:
Udacity Cloud DevOps Nanodegree Program
