# Terraform_Azure

Describe main.tf file for launching infrastructure on Azure cloud.

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
