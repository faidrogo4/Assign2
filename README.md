# Assign2
Uploaded files and folders in this repository are contents that are used for the website hosted in Assignment 2 CS4843.

# Overview
This is assignment was aimed to teach how to use infrastructure as code in AWS. Here, we created three different YAML files to build out the network, webserver, and database/storage via the AWS CLI. For the network, a VPC was defined that held two different instances. Both instances were created in both a private and public subnet. This was to create two different availability zones in the event that traffic overflowed in one of them. Furthermore, NAT Gateways were used in both zones (within the public subnet) so that the private subnets could access internet. Instances within the private subnet also rely on the security group granting access to the public subnet. For the webserver, instances and security were defined along with the load balancer. For the storage, a DBInstance was created and mysql was selected as the engine using the same availability zones as defined in the other yaml files.    

# Link
http://drs721-assign2-fidrogo.s3-website-us-west-2.amazonaws.com
