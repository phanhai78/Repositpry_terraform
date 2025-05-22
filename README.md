# 🌐 Terraform AWS Infrastructure Deployment

This project is a clone of [phanhai78/Repositpry_terraform](https://github.com/phanhai78/Repositpry_terraform.git) and is used to provision AWS infrastructure using Terraform.

## 📥 Clone the Repository

```bash
git clone https://github.com/your-username/Repositpry_terraform.git
cd Repositpry_terraform
```

## ⚙️ Prerequisites
Before running this project, ensure you have:
Terraform installed (v1.0+)

An active AWS account

Configured AWS credentials via the AWS CLI:

```bash
aws configure
```
Or, export environment variables:
```
export AWS_ACCESS_KEY_ID=your_access_key
export AWS_SECRET_ACCESS_KEY=your_secret_key
export AWS_REGION=your_region
```

🚀 Deploying Infrastructure

1. Initialize Terraform
```
terraform init
```

2. Review the execution plan
```
terraform plan
```

3. Apply the configuration
```
terraform apply
```


