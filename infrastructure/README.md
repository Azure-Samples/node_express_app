# Deploy a Node app service to Azure

## Create a a new Node webapp in Azure using GH Action workflows

This template deploys a web app with Node support to let us upload a Node-based app. The web app with Node is an app service that allows you to deploy your Node website. This will deploy a free tier Linux App Service Plan where you will host your app service.

If you are new to Azure App Service, see:

- [Azure App Service](https://azure.microsoft.com/services/app-service/web/)
- [Template reference](https://docs.microsoft.com/azure/templates/microsoft.web/allversions)
- [Quickstart templates](https://azure.microsoft.com/resources/templates/?resourceType=Microsoft.Compute&pageNumber=1&sort=Popular&term=web+apps)

If you are new to template deployment, see:

[Azure Resource Manager documentation](https://docs.microsoft.com/azure/azure-resource-manager/)

## Prerequisites

If you have already a Linux App Service Plan, you will have to deploy the new web app into the same resource group that the other web app is. That's because Student accounts has a limit of only 1 free tier Linux app service plan.

`Tags: Azure4Student, appServices , node, linux, Beginner`
