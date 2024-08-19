Net Core 8.0 Web API

Step 1: Create Webapi PlatformService
dotnet new webapi -n PlatformService

Step2: Add package Automapper, EntityFrameworkCore,Design,InMemory and SqlServer
dotnet add package AutoMapper.Extensions.Microsoft.DependencyInjection
dotnet add package Microsoft.EntityFrameworkCore
dotnet add package Microsoft.EntityFrameworkCore.Design
dotnet add package Microsoft.EntityFrameworkCore.InMemory
dotnet add package Microsoft.EntityFrameworkCore.SqlServer

Step3: Created Models Folder and create Platform.cs model class inside it.
Note: Model Created for internal data use.

Step4: Created Data Folder and created AppDbContext.cs class inside it. Implements DbContext from EntitiyFramework.

