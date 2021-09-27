# Cloud Infra Automation
Terraform module to deploy provision ec2 instances

access the module `main.tf`

Define your app params:


##vpc_id
    Your VPC id created to host the EC2 instances
    
##subnet_cidr
    A public subnet attached to the your VPC, defined above
    
##ssh_key
    Public ssh key to access the ec2 instances through ssh
    
##app_name
    Your application name, this name will be used to name all aws resources
    
##app_instance
    EC2 flavor to be assigned to you application machine

##db_instance
     EC2 flavor to be assigned to you database machine
