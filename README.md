# Azure Release Pipeline to Deploy Linux VM with ARM template.

## Introduction 
TODO: To deploy Linux virtual machine to azure using ARM Template and Azure DevOps Release Pipeline. 

## Getting Started
TOOLS: 
1.	VScode
2.	Azure DevOps
3.	GitHub
   

## Build and Test
TODO: 
Started empty ARM template from Azure portal.
Added Ubuntu VM as a resource
Opened Azure Cli to list available Skus in the targeted region
Checked Azure Quota to be sure the selected Sku will fly
Initiate a repository on Azure DevOps with README file
Created a new file by copying and pasting the content of the ARM template on Azure Portal [ARM template](ARM_Template_Vmubuntu).
Authenticate to Azure portal from Azure DevOps if not done before
Created Release pipeline to deploy the ARM template using classic pipeline [yaml script](Azure_Release_Pipeline)
Set up Stage in Release Pipeline by authenticating to Azure subscription and supplying needed parameters from the ARM template file.
Save the stage and deploy

## Challenge
Getting the right Sku and VM size with a low cost, available in the targeted region and withing the subscription Quota
