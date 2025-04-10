# Task-3-Iac-with-Terraform
In this repo there is simple main.tf file which defines Provision a local nginx container using Terraform.

## Steps to run main.tf file

### Clone this repo
```
git clone https://github.com/Pankajarya1058/Task-3-Iac-with-Terraform.git
```

### Install the terraform on your machine.
- [terraform](https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli)

### Run the following commands
```
terraform init
```
```
terraform plan
```
```
terraform apply
```
### Now, access the nginx container through browser
```
http://<machine-ip>
```
### To delete the nginx container
```
terraform destroy
```






