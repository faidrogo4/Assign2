# Assign2
Uploaded files and folders in this repository are contents that are used for the website hosted in Assignment 2 CS4843.

# Overview
This is assignment was aimed to teach how to use infrastructure as code in AWS. Here, we created three different YAML files to build out the network, webserver, and database/storage via the AWS CLI. For the network, a VPC was defined that held two different instances. Both instances were created in both a private and public subnet. This was to create two different availability zones in the event that traffic overflowed in one of them. Furthermore, NAT Gateways were used in both zones (within the public subnet) so that the private subnets could access internet.  
