# Overview
This project demonstrate the implementation of Continious Integation and Continious Delivery pipelines step by step by using a Python-based machine learning application and the Flask web framework in Github, Azure Portal and Azure DevOps platforms. 
After creating a Github Repository called AzureDevops, first Github Actions is used along with a Makefile, requirements.txt and application code to perform an initial lint, test, and install cycle to create Continuous Delivery.  Then this project was integrated with Azure Pipelines to enable Continuous Delivery to Azure App Service.
## Project Plan
<TODO: Project Plan

* A link to a Trello board for the project
* A link to a spreadsheet that includes the original and final project plan>

## Instructions

<TODO:  
* Architectural Diagram (Shows how key parts of the system work)>

<TODO:  Instructions for running the Python project. 

1. Create an [Azure Account](https://portal.azure.com) 
2. Install the [Azure command line interface](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli?view=azure-cli-latest)
3. Fork this repo to your GitHub account 
4. Clone this repository to your Azure CLI
5. Create ssh keys in Azure Cloud Shell and upload it to your GitHub account
6. For continuous integration, set up GitHub action as a build server—a centralized machine that is dedicated to continuously building the project every time code is committed to it set up a work flow 
7. Set up Azure DevOps Pipeline Agent (a virtual machine) to perform the pipeline jobs, such as building your code residing in Github and deploying it to the Azure services. To od this:
  - Create a Personal Access Token (PAT)
  - Create an Agent pool
  - Create a Linux VM
  - Configure the Linux VM as an Azure DevOps Build Agent
  - Install Application-specific depedencies
8. Set up a Service connection ensure via Azure Resource Manager and Service principal to connect your DevOps account with the Azure account.
9. Create a Web App Manually and initially deploy your app in Cloud Shell. Verify the deployed application works by browsing to the deployed URL. Go to https://<Your_unique_app_name>.azurewebsites.net/.
10. Create a Pipeline
* Project running on Azure App Service

* Project cloned into Azure Cloud Shell

* Passing tests that are displayed after running the `make all` command from the `Makefile`

* Output of a test run

* Successful deploy of the project in Azure Pipelines.  [Note the official documentation should be referred to and double checked as you setup CI/CD](https://docs.microsoft.com/en-us/azure/devops/pipelines/ecosystems/python-webapp?view=azure-devops).

* Running Azure App Service from Azure Pipelines automatic deployment

* Successful prediction from deployed flask app in Azure Cloud Shell.  [Use this file as a template for the deployed prediction](https://github.com/udacity/nd082-Azure-Cloud-DevOps-Starter-Code/blob/master/C2-AgileDevelopmentwithAzure/project/starter_files/flask-sklearn/make_predict_azure_app.sh).
The output should look similar to this:

```bash
udacity@Azure:~$ ./make_predict_azure_app.sh
Port: 443
{"prediction":[20.35373177134412]}
```

* Output of streamed log files from deployed application

> 

## Enhancements

<TODO: A short description of how to improve the project in the future>

## Demo 

<TODO: Add link Screencast on YouTube>


