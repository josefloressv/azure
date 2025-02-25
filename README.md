# Azure Play Ground

## Tools

```bash
# Install Azure SDK
brew install azure-cli
```

## Basic Commands

```bash
# Login with Azure
az login

# Use this for ACG or When using Incognito Windows
az login --use-device-code

# Logout
az logout

# Show account info
az account show

# Configure the Resource Group by default
az group list -o table
az configure --defaults group=1-22e5f5c3-playground-sandbox

```