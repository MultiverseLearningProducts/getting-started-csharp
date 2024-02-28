# Getting Started with C# and .NET

A basic CRUD API using C# and ASP.NET Core using the [Microsoft documentation](https://learn.microsoft.com/en-us/aspnet/core/tutorials/first-web-api?view=aspnetcore-7.0&tabs=visual-studio-code)

Video Demo: [Video tutorial](https://zoom.us/clips/share/O_r9UgPdCRActm9Q_0xrNERQTjguiLGIgjdRTWgVPP8zLl_5EaBq6iNa9hNM-Gb2AgZSiDT4dFy9vYhv9l3ztXPU.TeqPWolMSNnWPKkN)

## Installation

Install the following:
- IDE such as Visual Studio Code (VS Code) or Visual Studio
- If using VS Code, install the following VS Code C# extension: [C# Extension](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp)
- Install .NET: [.NET 7.0](https://dotnet.microsoft.com/download/dotnet/7.0) - or preferred version
- Optionally, you may also install the following VS Code extensions:
    - [C# Dev Kit](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csdevkit)
    - [.NET MAUI](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.dotnet-maui)
    - [Unity](https://marketplace.visualstudio.com/items?itemName=visualstudiotoolsforunity.vstuc)

## Setup
- Clone this repository.
- Open up this project in your IDE of choice such as VS Code or Visual Studio.

## Run Application Locally

Trust HTTP certificate

```bash
  dotnet dev-certs https --trust
```

Start the server

```bash
  dotnet run --launch-profile https
```

Start the server with .NET Hot Reload (to be able to make changes to the server without restarting):

```bash
  dotnet watch run --launch-profile https
```

## Testing

Test the API endpoints by:
- visting the https URL generated in the terminal with /swagger appended (e.g. https://localhost:7273/swagger)
- using a tool such as Postman or Thunder Client (https://localhost:7273)