# Terraform EC2 Instance Setup on AWS

This project uses **Terraform** to provision an **Amazon EC2 instance** in AWS. It was executed from **AWS CloudShell**.

## 📌 Prerequisites

- AWS account with appropriate IAM permissions
- AWS CloudShell access
- Terraform installed (pre-installed in CloudShell)

## 📁 Files

- `main.tf`: The main Terraform script for EC2 provisioning
- `README.md`: Project documentation

## ⚙️ Terraform Configuration Summary

- **Provider**: AWS
- **Region**: `us-east-1`
- **Resource**: EC2 instance (`t2.micro`)
- **AMI**: Amazon Linux 2 (default AMI ID used for the region)
- **Tags**: Name = "TerraformEC2"

## 🚀 How to Use

### 1. Clone the Repository in CloudShell

```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
2. Initialize Terraform
bash
Copy
Edit
terraform init
3. Review the Plan
bash
Copy
Edit
terraform plan
4. Apply the Configuration
bash
Copy
Edit
terraform apply
✅ Type yes when prompted to confirm.

5. Destroy Resources (Cleanup)
bash
Copy
Edit
terraform destroy
