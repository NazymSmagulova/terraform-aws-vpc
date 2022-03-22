# Terraform AWS VPC Module

### Usage
```
module "vpc" {
    source = "NazymSmagulova/vpc/aws"
    cidr_block = "10.0.0.0/16"
    private_subnets_cidr = ["10.0.1.0/24"]
    tags = {
        Name = "Dev"
    }
}
```