# DevOps-Project-Dynamic-Website-Hosting-on-AWS-AWS-console

This project demonstrates the deployment and hosting of a dynamic website on AWS using a comprehensive setup that includes Virtual Private Cloud (VPC), EC2 instances, Auto Scaling, Load Balancing, and other AWS services to ensure high availability, security, and fault tolerance.

Project Overview:

The primary objective of this project is to deploy a dynamic website on AWS using the following resources and configurations:

Virtual Private Cloud (VPC): Configured with both public and private subnets spanning two availability zones for enhanced reliability and fault tolerance.

Internet Gateway: Deployed to enable connectivity between the VPC instances and the wider internet.

Security Groups: Established to serve as a network firewall mechanism, controlling inbound and outbound traffic to the instances.

Public Subnets: Utilized for infrastructure components like the NAT Gateway and Application Load Balancer.

Private Subnets: Used to place web servers (EC2 instances) for enhanced security.

EC2 Instance Connect Endpoint: Implemented for secure connections to assets within both public and private subnets.

NAT Gateway: Allowed instances in both the private application and data subnets to access the internet.

EC2 Instances: Hosted the website within private subnets.

Application Load Balancer: Used to evenly distribute web traffic to an Auto Scaling Group of EC2 instances across multiple availability zones.

Auto Scaling Group: Automatically managed EC2 instances, ensuring website availability, scalability, fault tolerance, and elasticity.

Certificate Manager: Secured application communications.

Simple Notification Service (SNS): Configured to alert about activities within the Auto Scaling Group.

Route 53: Registered the domain name and set up a DNS record.

S3: Used to store application code.

 Repository Contents :

Reference Diagram: A detailed diagram illustrating the architecture and components used in this project.

Deployment Scripts: Scripts used to automate the deployment of resources and configurations.



![3 _Host_a_Dynamic_Web_App_on_AWS](https://github.com/Ahmedbo9/DevOps-Project-Dynamic-Website-Hosting-on-AWS-AWS-console/assets/65826519/9b60618c-a1ea-4f44-8534-df3b7ec48ba2)



