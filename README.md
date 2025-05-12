# Azure-AI-Foundry

## Description
            
 Azure AI Foundry hub is a container for all the resources needed to run an AI Foundry project. The hub includes a storage account, a key vault, and a workspace. The workspace is used to store the data and models used in the project. The storage account is used to store the data and models used in the project. The key vault is used to store the secrets used in the project.

## Deployment

```bash
Az login
export ARM_SUBSCRIPTION_ID=<subscription_id>
export ARM_TENANT_ID=<tenant_id>

Terraform init
Terraform plan
Terraform apply
```