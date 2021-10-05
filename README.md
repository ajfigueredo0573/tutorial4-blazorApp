# Blazor Starter Application

This template contains an example [Blazor WebAssembly](https://docs.microsoft.com/aspnet/core/blazor/?view=aspnetcore-3.1#blazor-webassembly) client application, a C# [Azure Functions](https://docs.microsoft.com/azure/azure-functions/functions-overview) and a C# class library with shared code.

## Getting Started

I created a repository from the [GitHub template](https://docs.github.com/en/enterprise/2.22/user/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template) and then cloned it locally to my machine .

Once I cloned the project, I opened the solution in [Visual Studio Code](https://code.visualstudio.com/) and followed these steps:

- Right click Client in Solution Explorer and click Open in Terminal
- Enter dotnet watch run
    **Note**: Make sure to save the project before doing the second step.

## Template Structure

- **Client**: The Blazor WebAssembly sample application
- **API**: A C# Azure Functions API, which the Blazor application will call
- **Shared**: A C# class library with a shared data model between the Blazor and Functions application

## Deploy to Azure Static Web Apps

- This application was deployed to [Azure Static Web Apps](https://docs.microsoft.com/azure/static-web-apps), to learn how, check out [our quickstart guide](https://aka.ms/blazor-swa/quickstart).
- I set up hosting on Azure following [Azure Static Web Apps with .NET and Blazor](https://devblogs.microsoft.com/aspnet/azure-static-web-apps-with-blazor/)
- Click link to my page [Blazor Starter](https://happy-bush-0d23c6310.azurestaticapps.net)

## Reference Links

- IPO code from [Blazor](https://sites.google.com/site/profvanselow/programming/languages/c_1/blazor)
- To Do list added from tutorial at [Build a Blazor todo list app](https://docs.microsoft.com/en-us/aspnet/core/tutorials/build-a-blazor-app)

## Special Notes

I want to thank the student assistants from my COP 3003 class for helping me get through the Visual Studio bugs
