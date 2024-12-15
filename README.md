# terraform-gcp

#To confirm that Terraform is installed, run the following command:
terraform --version

#Initialize Terraform
cd terraform-gcp
terraform init

#Rewrite the Terraform configuration files to a canonical format and style
terraform fmt
#The output should look like this: mynetwork.tf

#To initialize Terraform, run the following command:
terraform init

#Create an execution plan, run the following command:
terraform plan

#Apply the desired changes, run the following command:
terraform apply
