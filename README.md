# Description
AWS CloudFormation template for WordPress: This template installs a highly-available, scalable WordPress deployment using a multi-az Amazon RDS database instance for storage. It uses Ansible (pullmode) to install and configure the Wordpres inside the VM(s)"

# Installation
Download the cloudformation template using the the command - wget https://github.com/vinod810/AwsWordPress/raw/master/cloud-formation.json  You may then create the WordPress stack from the AWS cloudformation console - https://console.aws.amazon.com/cloudformation/

# Features
Highly Available
Autoscaling
Multi-AZ RDS 

# Roadmap 
CDN/ CloudFront
CloudWatch 
Elastic Cache for the RDS
Shared EFS for contents such as WordPress thems and pluggins
HTTPS/ SSL certificate
Encrypt RDS and EFS at rest
