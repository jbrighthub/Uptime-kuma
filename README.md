# Uptime-kuma
https://haci.io/posts/uptime-kuma-azure-container-instance/#deployment-to-azure

Uptime-kuma on Azure Container Instance integrate Azure File Share

az group create --name rg-test-dev-002 --location westeurope

az container create --resource-group rg-test-dev-002 --file deployment1.yaml
