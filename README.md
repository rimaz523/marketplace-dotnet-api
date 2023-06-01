[![Build Status](https://dev.azure.com/rimazmohommed523/Marketplace/_apis/build/status%2Frimaz523.marketplace-dotnet-api?branchName=master)](https://dev.azure.com/rimazmohommed523/Marketplace/_build/latest?definitionId=13&branchName=master)

# Online Marketplace Platform API Backend

## Description

This is the backend API app of a one-stop online marketplace site created with dotnet core 6.0 using the Clean Architecture design pattern.

## Technologies & Tools used in the front-end single page web application include:

- .Net Core 6.0
- Clean Architecture Pattern with Mediatr
- Fluent Validation
- Automapper
- Swagger
- CI/CD using Azure DevOps
## Installation Instructions

- Clone the project locally
- Ensure startup project is set to WebApi
- Run using kestrel or IIS on visual studio or and IDE of your choice.

## Developer Instructions

#### Code Formatting
- Code-style rules have been defined in editorconfig files in each project
- To format your code, either run `dotnet format` in the root dir OR run Code Analysis and Cleanup in Visual Studio IDE.
- Code format checks have been implemented in the CI/CD pipeline to ensure code that is merged from a PR is conforming to all the code-style rules in editorconfig.
- For more information see: https://dev.azure.com/rimazmohommed523/Marketplace/_wiki/wikis/Marketplace.wiki/36/Code-Formatting