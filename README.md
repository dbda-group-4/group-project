# Develop a CI/CD pipeline to deploy any application using Jenkins, Python, Shell Script on Cloud.

### Automation of creation and deployment of S3,AWS and Lambda on AWS using Jenkins Pipeline.

Getting Started
These instructions will help you setup Automated Cloud Services on Amazon Web Services.

### Prerequisites
* 1.AWS Account
* 2.Knowledge of Shell Script
* 3.Knowledge of Python
* 4.Jenkins
* 5.GitHub

### Preparing for Automation:
* 1.Log into you AWS Account.
* 2.Goto CloudFormation  and create EC2 CFT with preinstalled Jenkins, Git.
* 3.After successfull creation of EC2 instance go to the instance and copy IPv4 Public IP from EC2 and paste in URL with port 8080.
*  eg. x.x.x.x:8080
* 4.Get the password of jenkins from /var/lib/jenkins/secrets/initialAdminPassword path from EC2.
* 5.Click on "Install Suggested Plugins" and continue further steps for Jenkins Server to start.
* 6.Make a Repository in Git account and make a "Webhook" for the same.
* 7.Make a Jenkinsfile in repository.
* 8.Make a pipeline job in jenkins to build Jenkinfile and deploy it.

### Execution:
* 1.Make a json file in repository containig the CFT code of AWS services and make Jenkinfile refer it as template-body. 
* 2.Commit the changes in repository.
* 3.Build a jenkins job and give the parameters for it.
* 4.It will automatically compile, validate ,unit test and if successfully build it deploys the CFT stack in AWS.
* 5.Now once the CFT succeesfully complited you are ready to use requested service.

### Output

* You have succesfully created the requested AWS service through Jenkins Pipeline. 


### Built With
* AMAZON WEB SERVICES - Cloud service used
* SHELL SCRIPT - Scripting language
* PYTHON - Programming language
* Jenkins - Jenkins is an open source automation server
### Authors
* Dipansu Sinha - [Dipansu](https://github.com/Dipansu)
* Aniruddha Parte -  [aniruddhaparte61](https://github.com/aniruddhaparte61)
* Anuja Dalvi - [anujadalvi](https://github.com/anujadalvi)
* Harshal Ugale - [harshal-ugale](https://github.com/harshal-ugale)

### Acknowledgments
* Guided By : Suraj Kulkarni
* Guided By : Pradeep Tripathi
