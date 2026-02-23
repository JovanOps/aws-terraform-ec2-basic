# AWS Terraform Lab #1 – EC2 Deployment

## 📌 Overview
This project provisions a basic AWS infrastructure using Terraform.

## 🧱 Architecture
- Custom VPC
- Public Subnet
- Internet Gateway
- Route Table
- Security Group (HTTP open)
- EC2 instance (t3.micro)
- Ubuntu 22.04 AMI
- Nginx installed via user_data


🌍 Output

Public IP of the EC2 instance.

<img width="1920" height="945" alt="Screenshot (1150)" src="https://github.com/user-attachments/assets/186e3c9b-7334-4272-83fd-acba2223da59" />

🛑 Cleanup

terraform destroy used to avoid AWS charges.


## ⚙️ Terraform Commands
```bash
terraform init
terraform plan
terraform apply
terraform destroy
