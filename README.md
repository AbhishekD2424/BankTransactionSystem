# BankTransactionSystem
Bank Transaction System on Asp.Net Core using MVC CRUD Operations with EF Core

This is a project that I made for showing CRUD Operations ( Insert, Update, Delete, and Retrieve) with the latest ASP.NET Core 6.0 MVC using Entity Framework Core and SQL Server DB.

Points utilized :
- Create MVC Project
- Define EF Core Model
- Dependency Injection
- DB Connection String
- Database Migration
- Create MVC Controller
- Layout Page
- Insert Operation
- Form Validation in MVC
- Form Submission
- Display Existing Records
- Update Operation
- Delete Operation

NOTE: To execute this program make sure that the packages installed are the same as the Framework Dependencies of the project(6.0.22). Also, an SQL Server is being used in this program so SQL commands for migration have to be implemented and changes to the (appettings.json) file have to be done:
-	SQL Server connection string:
(connetionString="Data Source=ServerName;
Initial Catalog=DatabaseName;User ID=UserName;Password=Password")
- If you have a named instance of SQL Server, you'll need to add that as well:
("Server=localhost\sqlexpress")
- To see the SQL server name->Start->Run->(services.msc)->serach for SQL Server(name of SQL server)
- In NuGet Package Manager Console:(Error: SQL Services not in running state or connection string not in particular format)
Add-Migration "Initial Create"->Update-Database
