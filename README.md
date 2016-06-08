# NetCorepostgreSQLDocker
Project for linking two docker containers (.NET Core app/postgres db)

Contains:
  .NET Core MVC Project
  PostgreSQL Migrations (Identity)
  
Doesn't contain:
  PostgreSQL connection string (in appsettings.Development.json on local machine)
  Format - "ConnectionStrings": {
    "postgresCS" : "User ID = ; Password = ; Host = ; Port = ; Database = ; Pooling = true;"
  }
