# infotrixs

Week-1 Task

Overview
This project provides deployment instructions for both monolithic and microservices architectures using AWS EC2 instances. The application consists of WordPress and MySQL, and it is deployed on t2-micro instances with the Ubuntu AMI.

Monolithic Architecture

EC2 Instance: 1 t2-micro instance
Deployment: WordPress and MySQL are deployed on the same instance.

Microservices Architecture

EC2 Instances: 2 t2-micro instances
Instance 1: WordPress
Instance 2: MySQL

Prerequisites

AWS Account

EC2 Key Pair

Security Groups

Monolithic Deployment

Launch an EC2 instance with the t2-micro type and the ubuntu-* AMI.
Configure Security Group with the necessary rules.
SSH into the instance and deploy WordPress and MySQL.

Microservices Deployment

Launch two EC2 instances with the t2-micro type and the ubuntu-* AMI.
Configure Security Groups with the necessary rules.
SSH into each instance:
On the WordPress instance, deploy WordPress.
On the MySQL instance, deploy MySQL.
Welcome Page
Once the deployment is complete, access the welcome page using the public IP or domain of your instance.

Conclusion

Monolithic Architecture: Pros: Simplicity, easier to manage. Cons: Scalability challenges, single point of failure.

Microservices Architecture: Pros: Scalability, fault isolation. Cons: Increased complexity, potential communication overhead. Choose the architecture that best fits your application's requirements. Monolithic may be simpler for smaller projects, while microservices provide more flexibility for larger and scalable applications.
