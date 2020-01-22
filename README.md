# SimpleCRUD-system-using-Scaffold


Microsoft.VisualStudio.Web.CodeGeneration.Design -Version 3.0.0-preview8-19413-06 This package helps generate controllers and views.

Install-Package Microsoft.EntityFrameworkCore.Tools -Version 3.0.0-preview8.19405.11 This package helps create database context and a model class from the database.

Install-Package Microsoft.EntityFrameworkCore.SqlServer -Version 3.0.0-preview8.19405.11 The database provider allows Entity Framework Core to work with SQL Server.

Scaffold-DbContext “Server=ABCSERVER;Database=Inventory;Integrated Security=True” Microsoft.EntityFrameworkCore.SqlServer -OutputDir Models

Above three Nuget Package used and Scaffold-DbContext also use
