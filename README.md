# Deploy WebApp with Node to Azure 

The purpose of this sample app is to **deploy a web app with Node** using an **Azure web app** in few easy steps:

1. Create a new GitHub repository into your GH Organization using this template 
1. Configure AZURE_CREDENTIALS, AZURE_SUBSCRIPTION_ID and AZURE_WEBAPP_NAME as repo secrets
1. Trigger GitHub Action workflows:
    - provision Azure resources using ARM templates and manage your Infrastructure as code
    - build and deploy App code to Azure webapp
    - apply and manage Azure Policies as code
    - PR workflow : provision a review app, build and deploy App code to review app
   
   By making changes to the templates inside the folders of infrastructure,  policies, corresponding workflows could be triggered. By raisig a pull request, the PR workflow could be triggered.

# Standardize this as a new repo template within your GitHub organization

A GitHub repo template is a very convenient tool if you often start developing new projects and you and your teams need a preconfigured starting template with installed dependencies, structure and customized automation processes.

You can now leverage the repo structure and the workflow templates present in this sample repo and standardize the getting started experience for teams in your organization in just two steps: 

1. Create a new repo using this [repo template](https://github.com/Azure-Samples/node_express_app/generate) into your GH organisation. 

   (Optional) Customize the templates based on your enterprise requirements

2. Configure this new repo into a GitHub repo template. To do this, just go to the repository settings and click on the "Template repository" checkbox, and you're all set!




## Overview

**GitHub Actions** gives you the flexibility to build an automated software development lifecycle workflow. You can write individual tasks ("Actions") and combine them to create a custom workflow. Workflows are configurable automated processes that you can set up in your repository to build, test, package, release, or deploy any project on GitHub.

With **GitHub Actions** you can build end-to-end continuous integration (CI) and continuous deployment (CD) capabilities directly in your repository. 

### Prerequisites

1. You will need a **GitHub** account. If you do not have one, you can sign up for free [here](https://github.com/join)

1. **Microsoft Azure Account**: You will need a valid and active Azure account for this lab. If you do not have one, you can sign up for a [free trial](https://azure.microsoft.com/en-us/free/).
