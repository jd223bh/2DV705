# Prerequisites:

- Aws account with a IAM profile
- AWS cli V2
- Terraform >= 1.6 
- Git 


## Configure CLI Profile

Configure a CLI Profile with eu-north-1 using the IAM profile credentials

Create a profile with AWS_PROFILE=”profile name” 

## Create key pair 
Create an EC2 key pair named 2dv705 with the eu-north-1 region.

Save the key as ~/.ssh/2dv705.pem

Chmod 400 the .PEM file.


## Run the script 
Then run the script handover.bash when all prerequisites are fulfilled. 

The script will create a terraform.tfvars and apply the terraform plan


## Destroy
To destroy the instance run: 

terraform destroy
