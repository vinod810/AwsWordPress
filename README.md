# Description
*AWS CloudFormation template for WordPress:* This template installs a highly-available and scalable WordPress deployment using a multi-AZ Amazon RDS database for storage. It uses Ansible (pull-mode) to install and configure the Wordpress inside the VM(s)"

# Installation
Download the cloudformation template using the following command and then create the WordPress stack from the [AWS cloudformation console](https://console.aws.amazon.com/cloudformation/):

**wget https://github.com/vinod810/AwsWordPress/raw/master/cloud-formation.json**  

# Features
The following capabilities are currently supported:
1. Highly Available
2. Autoscaling
3. Multi-AZ RDS 
4. Private and Public subnets
5. Bastion node
6. Internet Gateway
7. NAT

# Roadmap 
The following capabilites will be considered to be included in the future releases:
1. CDN/ CloudFront
2. CloudWatch 
3. Elastic Cache for the RDS
4. Shared EFS for contents such as WordPress themes and pluggins
5. HTTPS/ SSL certificate
6. Encrypt RDS and EFS at rest
7. Geo-redenduncy using DNS and multi-region database replication
