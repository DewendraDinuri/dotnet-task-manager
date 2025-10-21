# dotnet-task-manager
.NET project 


Step 1: Setup Your Project
1️ Install .NET SDK

Go to ..  https://dotnet.microsoft.com/en-us/download

Download .NET 8 SDK (latest LTS version).
After installation, open your terminal (or PowerShell) and check:

dotnet --version


It should show something like 8.0.x.

2️ Create Folder & Initialize Git

In your terminal:

mkdir dotnet-task-manager
cd dotnet-task-manager
git init


Then create a new ASP.NET MVC project:

dotnet new mvc -n TaskManagerApp
cd TaskManagerApp


Run it:

dotnet run


Visit 👉 http://localhost:5000

You should see the default ASP.NET Core welcome pag
