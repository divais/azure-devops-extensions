# azure-devops-extensions
Sample 3rd party extensions extending the functionality of Test reporting tab in Azure DevOps pipelines

# Getting started

1. Initialize a new NPM package manifest:
 
   `npm init -y`
 
 2. Install the Microsoft VSS Web Extension SDK package and save it to your NPM package manifest:
 
    `npm install vss-web-extension-sdk --save`
 
# Package and publish your extension
1. From a command prompt, run the TFX tool's packaging command from your extension directory:

   `tfx extension create`
   
2. A .vsix file will be generated. Update your extension with the newly created .vsix file.

Read more about developing web extensions for Azure DevOps Services [here](https://docs.microsoft.com/en-us/azure/devops/extend/get-started/node?view=vsts)
