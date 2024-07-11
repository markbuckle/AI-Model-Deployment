# AI-Model-Deployment
How to Deploy AI Apps to the Cloud with Flask &amp; Azure

Steps:
1. Set up a [Microsoft Azure](https://portal.azure.com/) account if you don't already have one.
2. Create a Resource Group in the Azure Portal. A resource group helps you organize and manage resources based on their lifecycle and their relationship to each other. 
3. Click the 'Create Resurces' button
4. Search 'App Service'
5. Select 'Web App' and press 'create'
6. In the Azure Portal, fill out your new App Service details. Associate it with the LangChain-Experiments resource group. Set publish to Code, and select the correct Python version and your Region. Give it a global name, something like 'ai-docs-chatbot'. Finally, select an appropriate App Service Plan based on your needs. The free plan is fine for just getting started.
7. Press 'review + create' and then 'create' again. Once you see the notification "deployment suceeded' you should 'go to the resource'
8.** Deploy via GitHub repo: **In the Azure Deployment Center, connect your GitHub repository to your App Service and then click 'save'. This will enable continuous integration and deployment, so your app will be automatically updated whenever you push changes to the specified branch. Make sure to select the correct branch.
