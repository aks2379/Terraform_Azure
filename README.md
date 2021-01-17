# Terraform_Azure

Describe main.tf file for launching infrastructure on Azure cloud.

Part A - Infrastructure as a code (create terraform file to launch following on Azure)
Steps:
01. Create Resource group
02. Create Ddos protection
03. Create VPC
04. Create Subnet
05. Create Route Table
06. Associate Route table with subnet
07. Create security group for VM on all ports from everywhere
08. Associate subnet with security group
09. Create network interface
10. Create Ubuntu VM with disk/data delete on termination "ON" 

Part B - Launch using terraform
Steps:
01. terraform init - to initiate terraform - it will read provider block in the code and download supporting files for Azure
02. terraform plan - to check the code - it will validate the code and print if any defects also if clean will show what resources will be created as a result
03. terraform apply - to launch the resources on Azure
04. terraform destroy - to destroy created resources
