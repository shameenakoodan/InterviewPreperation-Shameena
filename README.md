# Cloud 

### What
    Cloud is a  massive network of computers owned by different providers like AWS
    Azure and GCP which we pay for and use to deploy our applications.
### How
    Deployed a nodejs application with MongoDB on AWS. Currently  working on a React  
    application that should be deployed on AWS and to use AWS s3 bucket for storing  files.
### Benefits
    Cost is the massive benefit because we only pay for what we use. We dont have to   
    worry about set up cost. We have multiavailablity of resources that means data and   
    applications are available at all time with limited outages.If one server   
    goes down other is available.Integrations are much more easier in cloud  

# DevOPS

### What
    DevOPS is a combination of culture and a way of working. DevOPS is a model of   working 
    were development and operations teams merge and work together  where they   work on the
    entire life cycle of the application starting from dev environment   setup,application
    development,testing and deploying the applications.A devops   engineer typically 
    automates a job.  

### How
    Currently working on a project to be deployed on cloud which should have a CI/CD pipeline 
    to automate the deployment  
### Benefits
    * Faster than traditional   
    * Continous delivery :   
    * Cost effective : We can spin down an app if it is not more required which saves a   
        lot of money  
    * Efficiency and effectivenes -evrything should be easy to use.  


## CI/CD
### What
    CI/CD is the process of continous integration and continous delivery and continous deployment.
    This is the process where where we automate the development and deployment.
### How
    We use Jenkins so that any time we make a push to the github it will be affected in the 
    deployed application
### Benefits
    * Allows to integrate small pieces of code which is inturn more manageable
    * Faster release of applications because for the every sprint a smaller version of 
        application is available
    * Easy maintenance
## Jenkins
### What
    Jenkins is a tool used to setup CI/CD using pipelines. With jenkins the code is pulled from a 
    repository like github. Any push to the github repository runs the application with new changes.

### How
    Created a pipeline to automate a node js application where the code is pulled from the git 
    hub repo.
### Benefits
    * It can be easily installed
    * It can be used on different platforms
    * It automates all integration work. 
    * It helps in saving time and money over the project lifecycle.
## Provisioning
### What
    Provisioning allows to automatically install software and its dependencies in a virtual environment
     like virtual box or vmware
### How
    We have a node application that requires a mongodb connection.
    Created an application environment with node in it and used bash to provision it
    Created a environemt for mongo and used bash to provision it. And these both are linked

### Benefits
    * The problem of it works in your system and not mine is solved because applications
        are run on VM's