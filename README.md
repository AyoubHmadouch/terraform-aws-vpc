# terraform-aws-vpc
Terraform module to create an AWS VPC with public/private subnets, route tables, Internet Gateway, and optional NAT Gateways.

## Module structure
├── main.tf          # Core resources
├── variables.tf     # Input variables
├── outputs.tf       # Module outputs
├── versions.tf      # Required providers & Terraform version
├── locals.tf        # Local values (naming conventions, computed vars)
├── README.md        # Documentation (inputs/outputs, examples)
└── examples/
   └── simple/      # Example usage of this module
       └── main.tf
