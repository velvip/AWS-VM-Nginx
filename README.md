# AWS VM-Nginx
Installing a virtual machine in "Amazon Web Services" with Nginx, using Terraform

# Quick Start
1. Use this instuctions to install [Terraform](https://learn.hashicorp.com/tutorials/terraform/aws-build?in=terraform/aws-get-started) and configurate AWS CLI 
2. Terraform will automatically search for saved API credentials in ~/.aws/credentials
3. Copy Main.tf,provider.tf,securitygroup.tf in one dirctory on you Linux PC
4. Use command `terraform init` to initialize a working directory containing Terraform configuration files
5. Use command `terraform apply` to create VM and install nginx
6. Go to public IP address your VM on port 80 (Http) and you see greetings nginx

