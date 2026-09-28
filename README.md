# Terraform AWS Module from Askar hehe 

## Example 

module "vpc-aws" {
  source  = "askarkaizen/vpc-aws/module"
  version = "0.0.2"

  # insert the 1 required variable here
  vpc_cidr = "10.0.0.0/16"
  subnet_cidr = ["10.0.1.0/24", "10.0.2.0/24"]
}




