# Demo: Call secured APIs from web applications

This completed project is the result of the lab exercise **Call secured APIs from web applications** that is referenced in the [README](../../README.md) in this repo.

## Prerequisites

- [Microsoft 365 tenant](https://developer.microsoft.com/office/dev-program?ocid=MSlearn)
- [.NET 5 SDK](https://dotnet.microsoft.com/download)
- [Visual Studio Code](https://code.visualstudio.com/)

## Run this Completed Project

- Create an Azure AD application by following the instructions in the lab exercise associated with this demo. In this step, you are instructed to collect these data elements:
  - Domain
  - TenantId
  - ClientId
  - ClientSecret
- Update the properties in the **[appsettings.json](./appsettings.json)** with the values you collected in the last step.
- Update the properties in the **[constants.cs](./constants.cs)** with the client Id of the web service application.
- Build and run the application by following the instructions in the lab exercise associated with this demo.
