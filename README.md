# Cloud Devops Engineer Capstone Project

This project is built using the skills learnt from Cloud Devops Engineer NanoDegree Program by Udacity.

## Skills Learned During the NanoDegree Program

* Working in AWS
* Using Jenkins or Circle CI to implement Continuous Integration and Continuous Deployment
* Building pipelines
* Working with Ansible and CloudFormation to deploy clusters
* Building Kubernetes clusters
* Building Docker containers in pipelines

## Project Guidelines
1. Propose and Scope the Project
* Plan what your pipeline will look like.
* Decide which options you will include in your Continuous Integration phase. Use either Circle CI or Jenkins.
* Pick a deployment type - either rolling deployment or blue/green deployment.
* For the Docker application you can either use an application which you come up with, or use an open-source application pulled from the Internet, or if you have no idea, you can use an Nginx “Hello World, my name is (student name)” application.
<br/>
2. Use Jenkins or Circle CI, and implement blue/green or rolling deployment.
* If you're using Jenkins, create your Jenkins master box and install the plugins you will need.
* If you're using Circle CI, set up your circle CI account and connect your git repository.
* Set up your environment to which you will deploy code.
</br>
3. Pick AWS Kubernetes as a Service, or build your own Kubernetes cluster.
* Use Ansible or CloudFormation to build your “infrastructure”; i.e., the Kubernetes Cluster.
* It should create the EC2 instances (if you are building your own), set the correct networking settings, and deploy software to these instances.
* As a final step, the Kubernetes cluster will need to be initialized. The Kubernetes cluster initialization can either be done by hand, or with Ansible/Cloudformation at the student’s discretion.
4. Build your pipeline
* Construct your pipeline in your GitHub repository.
* Set up all the steps that your pipeline will include.
* Configure a deployment pipeline.
* Include your Dockerfile/source code in the Git repository.
* Include with your Linting step both a failed Linting screenshot and a successful Linting screenshot to show the Linter working properly.
5. Test your pipeline
* Perform builds on your pipeline.
* Verify that your pipeline works as you designed it.
* Take a screenshot of the Circle CI or Jenkins pipeline showing deployment, and a screenshot of your AWS EC2 page showing the newly created (for blue/green) or modified (for rolling) instances. Make sure you name your instances differently between blue and green deployments.

## Get Started with the Project

In this project kubernetes clusters are deployed using Cloudformation.
The following clusters have been created in cloudformation:
1. VPC - It will create a virtual private cloud that has public subnets for Amazon EKS.
2. kubecluster - It will create EKS Cluster.
3. NodeInstances - It will create the nodes for EKS Custer.
4. Manager - It will create 2 hosts for managing EKS Cluster. 


Note - Please find the screenshots in Screenshots folder signifying successful running of the project.

