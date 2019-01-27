# Description
AWS CloudFormation template for WordPress: This template installs a highly-available, scalable WordPress deployment using a multi-az Amazon RDS database instance for storage. It uses Ansible (pullmode) to install and configure the Wordpres inside the VM(s)"

# Installation
Download the cloudformation template using the following command and then create the WordPress stack from the [AWS cloudformation console.](https://console.aws.amazon.com/cloudformation/):

**wget https://github.com/vinod810/AwsWordPress/raw/master/cloud-formation.json**  

# Features
1. Highly Available
2. Autoscaling
3. Multi-AZ RDS 

# Roadmap 
1. CDN/ CloudFront
2. CloudWatch 
3. Elastic Cache for the RDS
4. Shared EFS for contents such as WordPress themes and pluggins
5. HTTPS/ SSL certificate
6. Encrypt RDS and EFS at rest
