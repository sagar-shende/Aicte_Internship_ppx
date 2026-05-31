# Azure AI Agent Automation 🚀

A Terraform-based Infrastructure as Code (IaC) project to automate Microsoft Azure resource provisioning — built as a capstone project for the Microsoft Elevate × AICTE Internship Program.

## 📌 Problem Statement
Manual configuration in the Azure portal leads to **Configuration Drift**, human errors, and slow scaling. This project solves that with full automation.

## 🛠️ Tech Stack
- **Platform:** Microsoft Azure Cloud
- **IaC Tool:** HashiCorp Terraform (>= 1.9.0)
- **Provider:** azurerm (~> 4.8.0)
- **Language:** HCL (HashiCorp Configuration Language)

## ⚙️ Deployment Steps
```bash
terraform init    # Install Azure provider
terraform plan    # Preview changes
terraform apply   # Deploy resources
```

## 📦 Resources Created
- Azure Resource Group (`ai-agent-environment`, East US)
- Azure Storage Account (with configurable name via variables)

## 📊 Result
Machine Learning model (Bike Count Prediction) deployed with Azure storage backend — predicted vs actual counts validated successfully.

## 🔮 Future Scope
- Azure OpenAI & Cognitive Services integration
- Azure Functions for serverless automation
- CI/CD via GitHub Actions / Azure DevOps
- Azure Key Vault for secrets management
- Azure Monitor + Log Analytics

## 📚 References
- [Terraform Azure Provider Docs](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs)
- [Microsoft Azure Documentation](https://learn.microsoft.com/en-us/azure/)

## 🏆 Internship
**Microsoft Elevate × AICTE** | Power BI for Business Applications  
📅 20 Jan 2026 – 12 Feb 2026 | Student: Sagar Kishor Shende
